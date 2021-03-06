## Change Log

### Unreleased

### 0.7.1

- Fix index checks level and message

### 0.7.0

- Check `field-foreign-key-index` now accepts `when: indexes` instead of `when: unique_toegether` because now it search for duplicate indexes in `Meta.indexes`, `Meta.unique_toegether` and `Meta.constraints`
- Add checks:
    - `no-unique-together`
    - `no-index-together`

### 0.6.0

- Add checks:
    - `field-default-null`

### 0.5.0

- Fix `ignore_checks`
- Skip models fields not inherited from `fields.Field`
- Add `ignore_types` option

### 0.4.1

- Fix message for `field-verbose-name-gettext-case`

### 0.4.0

- Add infra for rest framework serializers checks
- Add checks:
    - `drf-model-serializer-extra-kwargs`
    - `drf-model-serializer-meta-attribute`
    - `model-admin`

### 0.3.0

- Add `include_apps` option.
- Fix ast crashes.

### 0.2.1

- Fix ast parsing of indented block #1

### 0.2.0

- First public release

### 0.1.0

- First alpha
