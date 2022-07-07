# Relationship

This pane is only shown when configuring relational fields (including images and translations). Depending on the type of
relationship, you'll be presented with one of the following set of options:

- [Many-to-One](/configuration/data-model/relationships/#many-to-one-m2o)
- [One-to-Many](/configuration/data-model/relationships/#one-to-many-o2m)
- [Many-to-Many](/configuration/data-model/relationships/#many-to-many-m2m)
- [Many-to-Any](/configuration/data-model/relationships/#many-to-many-m2m)
- [Translations](/configuration/data-model/relationships/#translations-o2m)
- [One-to-One]()

::: tip Corresponding Field

[Relationships go both ways](/configuration/data-model/relationships/#perspective-matters), so when creating a new
relation Field, Directus offers to automatically create the corresponding Field on the related Collection.

:::

<!--
-- M2O
**Relational Triggers** allow you to control what happens when a relationship is broken. There is one option:

- **On Delete of [Related Collection]** — When the related item (O2M) is deleted...
  - Nullify the parent M2O field (default)
  - Set the parent M2O field to its default value
  - Delete the parent collection's item (cascade)
  - Prevent the deletion
  -->
