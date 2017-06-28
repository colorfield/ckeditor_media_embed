Drupal 7 wrapper for the [CKeditor Media Embed](http://ckeditor.com/addon/embed) ('embed') plugin.
The [Drupal 8 implementation](https://www.drupal.org/project/ckeditor_media_embed) is way better than a wrapper, but here is a
quick 'backport' so Drupal 7 users can use it as well.

## Installation

Uncompress [CKEditor](http://ckeditor.com/) in sites/all/libraries/ckeditor (Tested on the 4.7.0 release), so the ckeditor.js file lives in sites/all/libraries/ckeditor/ckeditor.js.

Uncompress the following plugins in the sites/all/libraries/ckeditor/plugins directory.

- [Auto Embed](http://ckeditor.com/addon/autoembed)
- [Auto Link](http://ckeditor.com/addon/autolink)
- [Media Embed](http://ckeditor.com/addon/embed)
- [Media Embed Base](http://ckeditor.com/addon/embedbase)
- [Semantic Media Embed](http://ckeditor.com/addon/embedsemantic)
- [Line Utilities](http://ckeditor.com/addon/lineutils)
- [Notification](http://ckeditor.com/addon/notification)
- [Notification Aggregator](http://ckeditor.com/addon/notificationaggregator)
- [Widget](http://ckeditor.com/addon/widget)
- [Widget Selection](http://ckeditor.com/addon/widgetselection)

Enable this module.

Check 'Embed' in the Full HTML wysiwyg profile (admin/config/content/wysiwyg/profile/full_html/edit).
