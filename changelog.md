# 1.0.7

-   Fix image reference detection pattern, other minor fixes.

# 1.0.6

-   Bug fix: update current directory path before processing of Markdown file content, not after.

# 1.0.5

-   Do not rewrite source Markdown file if an error occurs.

# 1.0.4

-   Do not use image path when computing MD5 hash.
-   Add `targets` config option.
-   Add logging.

# 1.0.3

-   Take into account the content of image file when computing MD5 hash.

# 1.0.2

-   Add support of any local paths. Add image cache.
-   Remove `mogrify_path` and `diagrams_cache_dir` options, add `convert_path` and `cache_dir` instead.

# 1.0.1

-   Add `diagrams_cache_dir` option support.
