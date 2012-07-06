# Symbolset Sass

Sass helpers for Symbolset.

*Note: You will need to have the Symbolset font(s). [Get them from Symbolset](https://symbolset.com/).*

## Usage

    @import 'symbolset';
    
    .retweet:before {
      content: ss-standard-icon(retweet);
    }
    
    .twitter:before {
      content: ss-social-icon(twitter);
    }
