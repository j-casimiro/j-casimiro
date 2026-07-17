"Long-term consistency beats short-term intensity."

## Technologies

```typescript
type TechCategory = readonly [category: string, skills: readonly string[]];

const j_casimiro = [
  ["Languages",             ["typescript", "javascript", "python", "php"]],
  ["TypeScript Ecosystem",  ["zod", "tRPC", "tsx", "ts-node", "utility types"]],
  ["Mobile",                ["react native", "Expo"]],
  ["Frameworks",            ["nextjs", "nestjs", "reactjs", "expressjs", "vuejs", "django", "laravel"]],
  ["CSS",                   ["bootstrap", "tailwind"]],
  ["Databases",             ["postgresql", "mysql", "supabase", "redis", "sqlite"]],
  ["Auth",                  ["jwt", "sso", "firebase", "mfa"]],
  ["ORM",                   ["prisma", "drizzle", "laravel eloquent ORM", "django ORM"]],
  ["Tools",                 ["github", "git", "figma", "canva", "bruno", "vscode", "postman"]],
  ["DevOps/Cloud",          ["aws", "render", "vercel", "netlify", "railway", "docker", "kubernetes"]],
  ["OS",                    ["linux", "macos"]]
] as const satisfies readonly TechCategory[];
```
