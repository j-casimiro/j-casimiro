"We cannot solve our problems with the same thinking we used when we created them." — Albert Einstein

## Tech Stack

```typescript
type TechCategory = [category: string, skills: readonly string[]];

const jcas = [
  ["Languages",     ["typescript", "javascript", "python", "php"]],
  ["TS Ecosystem",  ["zod", "tRPC", "tsx", "ts-node", "utility types"]],
  ["Mobile",        ["react native"]],
  ["Frameworks",    ["nextjs", "nestjs", "reactjs", "expressjs", "vuejs", "nodejs", "django", "laravel"]],
  ["CSS",           ["bootstrap", "tailwind"]],
  ["Databases",     ["postgresql", "mysql", "supabase", "redis", "sqlite"]],
  ["Auth",          ["jwt", "sso", "firebase", "mfa"]],
  ["ORM",           ["prisma", "drizzle", "laravel eloquent", "django ORM"]],
  ["Tools",         ["github", "git", "figma", "canva", "bruno", "vscode", "postman"]],
  ["DevOps/Cloud",  ["aws", "render", "vercel", "netlify", "railway", "docker", "kubernetes"]],
  ["OS",            ["linux", "macos"]]
] as const satisfies TechCategory[];
```
