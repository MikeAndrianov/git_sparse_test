git sparse-checkout init --cone
git sparse-checkout set <dir1> <dir2>


add to QS github:

gem 'engine_test', git: 'https://github.com/MikeAndrianov/git_sparse_test', glob: 'engine_test/*.gemspec'
