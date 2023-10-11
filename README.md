# renovate-config

## Usage

automerge preset
```json:
{
  "extends": ["github>cizneeh/renovate-config:auto.json5"]
}
```

manual merge preset
```json: renovate.json
{
  "extends": ["github>cizneeh/renovate-config:manual.json5"]
}
```

## json5?

renovateは[json5での設定をサポート](https://docs.renovatebot.com/configuration-options/)しており、config repositoryを作るときも[json5が使える](https://docs.renovatebot.com/config-presets/#github)らしいが、json schemaをjson5に適用することは出来ない[らしい](https://json-schema-everywhere.github.io/json5)。

コメントを書きたいのでスキーマは諦めてjson5にした