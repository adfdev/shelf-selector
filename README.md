# Shelf selector (Inspired Arc icon selector)

This component is inspired by how Arc makes you choose its app icon. 🖥 Watch the demo video to see the component live in action!

[![IMAGE ALT TEXT HERE](https://img.youtube.com/vi/MAK85LsmjJc/0.jpg)](https://www.youtube.com/watch?v=MAK85LsmjJc)

# ⚡️ TECHNOLOGIES

- React
- Tailwind CSS
- Typescript

# ⚙️ HOW IT WORKS

```js
const items = [
{
  src: `/images/arc-icon/1.png`,
},
{
  src: `/images/arc-icon/2.png`,
},
...
]
```

```js
<ADFSchelfSelector
  className="w-full max-w-lg"
  selected={selectedIndex}
  onSelect={(index) => setSelectedIndex(index)}
  items={items}
/>
```

# Change color indicator or sides fade color with:

```js
<ADFSchelfSelector
   ...
  classNameSides?: string;
  classNameIndicator?: string;
/>
```

# Replace this following default classes:

```css
classNameSides = "via-white to-white",
classNameIndicator = "bg-blue-500 shadow-blue-500",
```

# Links
👉 [Get Shelf selector](https://adfdev.gumroad.com/l/shelf-selector-inspired-arc-icon-selector)

👉 [GumRoad @adfdev](https://adfdev.gumroad.com)

⚡️ [Website](https://adf.dev)
