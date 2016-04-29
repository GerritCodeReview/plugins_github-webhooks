include_defs('//bucklets/gerrit_plugin.bucklet')

MODULE = 'com.googlesource.gerrit.plugins.github.webhooks'

gerrit_plugin(
  name = 'github-webhooks',
  srcs = glob(['src/main/java/**/*.java']),
  resources = glob(['src/main/**/*']),
  manifest_entries = [
    'Gerrit-PluginName: github-webhooks',
    'Gerrit-Module: com.googlesource.gerrit.plugins.github.webhooks.Module',
    'Implementation-Title: GitHub Webhooks',
    'Implementation-URL: https://gerrit-review.googlesource.com/#/admin/projects/plugins/github-webhooks',
  ],
)
