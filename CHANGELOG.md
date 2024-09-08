# Changelog

## 2024-06-09

- Omit `as` prop from types for Headless UI-based components

## 2024-06-26

- Update `@headlessui/react` dependency to `v2.1.1`
- Update `Dialog`, `Alert`, and `Listbox` to new data-attribute-based transition API

## 2024-06-21

- Update `@headlessui/react` dependency to `v2.1.0`
- Use `DialogBackdrop` in `Alert` and `Dialog` components
- Update to new data-attribute-based transition API

## 2024-06-19

- Prevent content from overflowing the mobile sidebar

## 2024-06-18

- Use consistent `let` and `const` declarations
- Use consistent `clsx` import
- Use consistent `forwardRef` instead of `React.forwardRef` import
- Update `tailwindcss`, `prettier` and `prettier-plugin-tailwindcss` dependencies in Next.js demo app
- Fix class order in `Dropdown` component

## 2024-06-10

- Add `dark:[color-scheme:dark]` class to `Input` component ([#1596](https://github.com/tailwindlabs/tailwindui-issues/issues/1596))

## 2024-05-31

- Add Next.js demo app ([#1580](https://github.com/tailwindlabs/tailwindui-issues/issues/1580))
- Fix `Avatar` sizing and padding ([#1588](https://github.com/tailwindlabs/tailwindui-issues/issues/1588))

## 2024-05-27

- Add `pointer-events-none` to `InputGroup` icon ([#1594](https://github.com/tailwindlabs/tailwindui-issues/issues/1594))
- Add default text color to `Table` component ([#1581](https://github.com/tailwindlabs/tailwindui-issues/issues/1581))
- Fix TypeScript issues when using `as={Link}` ([#1582](https://github.com/tailwindlabs/tailwindui-issues/issues/1582))
- Fix `SidebarItem` import ([#1582](https://github.com/tailwindlabs/tailwindui-issues/issues/1582))
- Add `isolate` class to `InputGroup`, `SidebarLayout`, and `StackedLayout` components
- Fix comment indentation and use proper DocBlocks

## 2024-05-24

- Add new `SidebarLayout` component
- Add new `StackedLayout` component
- Add new `Navbar` component
- Add new `Sidebar` component
- Add new `DescriptionList` component
- Add new `Heading` component
- Add new `Divider` component
- Add new `framer-motion` dependency
- Update `@headlessui/react` dependency to `v2.0`
- Remove `as={Fragment}` from the transition components
- Improve and fix a number of types
- Made formatting of `className` and `{...prop}` more consistent across all components
- Made formatting of `forwardRef` consistent across all components
- Update `PaginationGap` component to use a `span` instead of a `div`
- Update the `SidebarHeading` to render use an `h3` instead of a `d`iv
- Remove `children` prop from `Switch` component

## 2024-01-08

- Add `resizable` prop to `Textarea` component ([#1543](https://github.com/tailwindlabs/tailwindui-issues/issues/1543))

## 2024-01-03

- Change top-level `let` declarations to `const`
- Fix `--btn-hover-overlay` color for dark/white button ([#1538](https://github.com/tailwindlabs/tailwindui-issues/issues/1538))
- Add `forwardRef` to `Input`, `Select`, and `Textarea` components ([#1540](https://github.com/tailwindlabs/tailwindui-issues/issues/1540))

## 2023-12-20

- Initial release
