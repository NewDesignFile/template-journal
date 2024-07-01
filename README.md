### Rough Notation

Based on the [Rough Notation](https://roughnotation.com/) library. You can use `<Notation />` component in your MDX content, such as:

```mdx
In Swift, the `Codable` protocol is a type alias for the <Notation type="box" color="blue">`Encodable` and `Decodable`</Notation> protocols:
```

And following is the type of this component:

```tsx
type Props = {
  type?: "underline" | "circle" | "crossed-off" | "highlight" | "strike-through" | "bracket";
  color?: string;
  strokeWidth?: number;
};
```

### Integrations

- @astrojs/mdx: https://docs.astro.build/en/guides/markdown-content/
- @astrojs/rss: https://docs.astro.build/en/guides/rss/
- @astrojs/sitemap: https://docs.astro.build/en/guides/integrations-guide/sitemap/
- @astrojs/tailwind: https://docs.astro.build/en/guides/integrations-guide/tailwind/
- rough-notation: https://roughnotation.com/


