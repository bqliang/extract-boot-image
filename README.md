# Extract Boot Image

这是一个利用 Github Action 从 `payload.bin` 文件中提取 `boot.img` 的项目。用户只需 Fork 本项目，然后从 [xiaomirom.com](https://xiaomirom.com/) 找到适用于自己手机的卡刷包下载地址，运行 GitHub Action 并填入卡刷包下载地址，等待运行完成后即可下载 `boot.img.zip` 文件，解压后即可获取 `boot.img`。

## 使用方法

以下是使用此项目的步骤：

1. Fork 本项目到您的 GitHub 账号下;
2. 找到适用于您手机型号的卡刷包下载地址。您可以在 [xiaomirom.com](https://xiaomirom.com/) 网站上查找适用于您的手机型号的卡刷包下载链接;
3. 进入您 Fork 的项目页面;
4. 点击上方的 "Actions" 选项卡;
5. 在 Actions 页面中，您将看到一个名为 "Extract Boot Image" 的 workflow，点击它;
6. 在 workflow 页面中，点击右上方的 "Run workflow" 按钮；
7. 在弹出的对话框中，填入卡刷包下载地址，并点击 "Run workflow" 按钮以开始运行工作流程；
8. 等待工作流程运行完成。您可以在页面上查看运行日志以跟踪进度；
9. 一旦工作流程运行完成，您将在页面上看到一个名为 "boot.img.zip" 的文件。点击该文件以下载它；
10. 解压下载的 `boot.img.zip` 文件，您将得到 `boot.img`。

## 注意事项

- 工作流程运行时间取决于卡刷包的大小和网络连接速度，请耐心等待完成。
- 如果工作流程运行失败，请检查填写的卡刷包下载地址是否正确，并确保网络连接正常。

## 贡献

如果您发现任何问题或改进的空间，请随时提出 Issue 或提交 Pull Request。我们欢迎并感谢您的贡献。

## 许可证

此项目采用 MIT 许可证。有关详细信息，请参阅 [LICENSE](LICENSE) 文件。