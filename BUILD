load("//tools/bzl:plugin.bzl", "gerrit_plugin")

gerrit_plugin(
    name = "github-webhooks",
    srcs = glob(["src/main/java/**/*.java"]),
    resources = glob(["src/main/resources/**/*"]),
    manifest_entries = [
        "Gerrit-PluginName: github-webhooks",
        "Gerrit-Module: com.googlesource.gerrit.plugins.github.webhooks.Module",
        "Implementation-Title: GitHub Webhooks",
        "Implementation-URL: https://gerrit-review.googlesource.com/#/admin/projects/plugins/github-webhooks",
    ],
)
