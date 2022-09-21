---
title: Author Post Count
date: 2020-09-05T08:30:40-08:00
lastmod: 2020-09-05T08:30:40-08:00
weight: "0"
description: D﻿isplays the number of posts by a specific author
snippet:
  code: |-
    // Add Shortcode
    function get_author_post_count( $atts ) {

    	// Attributes
    	$atts = shortcode_atts(
    		array(
    			'author_id' => '1',
    			'post_type' => 'post',
    		),
    		$atts,
    		'author_post_count'
    	);

    		$post_type = explode(',', $atts['post_type']);
    	
    		return count_user_posts( $atts['author_id'], $post_type );
    	

    }
    add_shortcode( 'author_post_count', 'get_author_post_count' );
  lang: phtml
---
D﻿isplays the number of posts by a specific author

**A﻿ttributes**

`author_id` *string*
`post_type` *string* or comma-separated list (no space)