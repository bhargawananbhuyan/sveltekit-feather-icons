# sveltekit-feather-icons

Type-safe Feather icons support for Sveltekit.

**Update:** Support for Tailwind classes as well as custom global CSS classes.

## Usage

```svelte
<script>
	// can be imported like this
	import { Feather } from 'sveltekit-feather-icons'
	// or this
	import Feather from 'sveltekit-feather-icons/feather.svelte'
</script>

<Feather icon="github" />

<Feather icon="github" size="18" classes="text-blue-500" />
```

## Parameters

The parameters that can be passed to `Feather` component are &mdash;

### Required

| Field name | Type   | Description                                                          |
| ---------- | ------ | -------------------------------------------------------------------- |
| icon       | string | name of icon; for reference search [here](https://feathericons.com/) |

### Optional

| Field name | Type   | Description                                           |
| ---------- | ------ | ----------------------------------------------------- |
| size       | string | size of icon                                          |
| color      | string | color of icon                                         |
| classes    | string | Tailwind classes as well as custom global CSS classes |
