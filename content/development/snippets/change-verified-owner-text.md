---
title: Change Verified owner text
date: 2022-09-09T17:05:49.989Z
description: Change the text indicating a verified owner of a WooCommerce Review
snippet:
  code: |-
    function change_text( $translated_text ) {
        if ( 'verified owner' === $translated_text ) {
            $translated_text = 'verified buyer';
        }
        return $translated_text;
        }
    add_filter( 'gettext', 'change_text', 20 );
  lang: php
---
Use this snippet in functions.php to change the text indicating a verified owner of a WooCommerce Review from 'verified owner' to 'verified buyer' or replace the \`$translated_text\` variable to the desired string.