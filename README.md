# ⚠️ Archived due to new feature proposed in original repository [see issue](https://github.com/imjuni/ctix/issues/14).

~## ctix without full file path alias in default export~

~This package changes default exports generation from [ctix](https://github.com/imjuni/ctix):~

```typescript
// instead original ctix:
export { default as srcPathToMyModule } from './src/path/to/MyModule';

// changes to:
export { default as MyModule } from './src/path/to/MyModule';
```

~## Usage~

~Use `npx @ggondim/ctix` instead original `npx ctix`.~
