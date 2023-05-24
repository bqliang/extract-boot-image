# Extract Boot Image

This is a project that utilizes GitHub Actions to extract `boot.img` from the `payload.bin` file. Users simply need to fork this project and obtain the download link for the appropriate firmware package for their specific phone model from [xiaomirom.com](https://xiaomirom.com/). By running the GitHub Action and providing the firmware package download link, users can wait for the process to complete and then download the `boot.img.zip` file, which can be extracted to obtain the `boot.img` file.

## Usage

Here are the steps to use this project:

1. Fork this project to your GitHub account.
2. Find the download link for the firmware package that is suitable for your phone model. You can search for the firmware package download link for your specific phone model on the [xiaomirom.com](https://xiaomirom.com/) website.
3. Go to the project page of your forked repository.
4. Click on the "Actions" tab at the top.
5. On the Actions page, you will see a workflow named "Extract Boot Image". Click on it.
6. On the workflow page, click on the "Run workflow" button at the top right corner.
7. In the pop-up dialog, enter the firmware package download link and click the "Run workflow" button to start the workflow execution.
8. Wait for the workflow to complete. You can view the execution logs on the page to track the progress.
9. Once the workflow is finished, you will see a file named "boot.img.zip" on the page. Click on it to download.
10. Extract the downloaded `boot.img.zip` file to obtain the `boot.img` file.

## Notes

- The execution time of the workflow depends on the size of the firmware package and the network connection speed. Please be patient and wait for the process to complete.
- If the workflow fails to run, double-check the provided firmware package download link for accuracy and ensure that your network connection is stable.

## Contributing

If you encounter any issues or have ideas for improvements, please feel free to raise an issue or submit a pull request. We welcome and appreciate your contributions.

## License

This project is licensed under the MIT License. For more information, please refer to the [LICENSE](LICENSE) file.