# app
pnpm init
# 新建pnpm-workspace.yaml
# 官网配置
(
    packages:
        - 'packages/*'
)
pnpm i vue -w
# 新建.npmrc
{
    shamefully-hoist = true
}