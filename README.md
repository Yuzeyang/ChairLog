# egg-logger-snippets README

egg日志vscode插件，方便懒人添加日志，规范团队日志

## Features

支持js和ts文件。

支持三种级别日志：info、warn和error。

支持两种日志格式：无参数及多参数格式。

## Snippets

`cli`: 快捷创建无参数info类型日志。

```typescript
this.ctx.logger.info('[info][function][info]');
```

`clia`: 快捷创建多参数info类型日志.

```typescript
this.ctx.logger.info('[info][rpc/test/functionName][scene] (var)(%j)', value);
```

`clw`: 快捷创建无参数warn类型日志。

```typescript
this.ctx.logger.warn('[warn][function][info]');
```

`clwa`: 快捷创建多参数warn类型日志。

```typescript
this.ctx.logger.warn('[warn][rpc/test/functionName][scene] (var)(%j)', value);
```

`cle`: 快捷创建无参数error类型日志。

```typescript
this.ctx.logger.error('[error][function][info]');
```

`clea`: 快捷创建多参数error类型日志。

```typescript
this.ctx.logger.error('[error][rpc/test/functionName][scene] (var)(%j)', value);
```

## Release Notes

### 1.0.0

支持基础日志快捷输出

**Enjoy!**
