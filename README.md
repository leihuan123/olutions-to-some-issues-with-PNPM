# olutions-to-some-issues-with-PNPM
pnpm operation not permitted symlink、pnpm operation not permitted unlink，Waiting for the problem to be resolved
# 1、pnpm operation not permitted symlink
权限问题，使用管理员身份运行cmd窗口，如果不能解决可能是其他杀毒软件问题需要全部关闭，再重新install
# 2、pnpm operation not permitted unlink
网络或者权限问题，重启电脑使用管理员身份运行cmd窗口，如果不能解决可能是其他杀毒软件问题需要全部关闭，再重新install，
# 3、pnpm--force
强制重新安装依赖：重新获取存储中修改的包，重新创建由不兼容版本的 pnpm 创建的锁定文件和/或模块目录。安装所有可选依赖，即使它们不满足当前环境（cpu、操作系统、arch）

# 4、pnpm安装后执行pnpm命令无效问题
 nvm管理的ndoe要配置他那个sytemlink的环境，还要打开这个策略 Set-ExecutionPolicy -ExecutionPolicy Unrestricted -Scope Process
