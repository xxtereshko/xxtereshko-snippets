# xxtereshko-snippets

`cl`

```tsx
console.log("$1 =>", $1)
```

`rf`

```tsx
type T$1Props = {}

export const $1 = ({}: T$1Props) => {
  return $0
}
```

`rfe`

```tsx
type T$1Props = {}

const $1 = ({}: T$1Props) => {
  return $0
}

export default $1
```

`us`

```tsx
const [$1, set$1] = useState($2)
```

`ue`

```tsx
useEffect(() => {
  $0
}, [$1])
```

`uer`

```tsx
useEffect(() => {
  $2

  return () => {
    $3
  }
}, [$1])
```

`ule`

```tsx
useLayoutEffect(() => {
  $2
}, [$1])
```

`uler`

```tsx
useLayoutEffect(() => {
  $2

  return () => {
    $3
  }
}, [$1])
```

`ha`

```tsx
const $1 = ($2) => {
  $0
}
```

`dob`

```tsx
const { $2 } = $1
```

`dar`

```tsx
const [$2] = $1
```

`sti`

```tsx
setInterval(() => {
  $2
}, $1)
```

`sto`

```tsx
setTimeout(() => {
  $2
}, $1)
```

`stb`

```tsx
import { ComponentMeta, ComponentStory } from '@storybook/react-native'

const Meta: ComponentMeta<typeof ${1}> = {
  title: '2;1',
  component: ${}
  args: {},
}

export default Meta

type T${1:}Story = ComponentStory<typeof ${1:}>

export const Default: T${1:}Story = args => <${1:} {...args} />
}



```

Enjoy! ❤️
