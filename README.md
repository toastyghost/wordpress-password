  WordPress Password Module for Drupal 7.x
============================================

This is a Drupal 7 module that implements PHPass (the third-party crypto library used by WordPress) to allow seamless login after a WordPress-to-Drupal migration, without the site ever being aware of the stored password. It works in conjunction with a command-line migration script that saves the PHPass hash for the unknown password to Drupal's user.data blob.
