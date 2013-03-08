Drop .chef/plugins/knife/source_ingredient_virtualbox.rb
into your .chef/plugins/knife directory and run:

```
knife source ingredient virtualbox
```

:file_cache_path and :data_bag_path must writable and might need to be set in your knife.rb

The latest available versions of virtualbox will be downloaded into
your file_cache_path and your data bag path will get a virtualbox directory
created which will be populated with data bag items for each version
of vagrant that is available.

