# BRCircularProgressBar
This project provides a multipurpose head-up display (HUD). This circular HUD is visually relayed on screen as part of the user interface. It is especially helpful when you are trying to display download, upload, and timer progress.

![giphy](https://media.giphy.com/media/11qvJd5e127XSU/giphy.gif)


# Initialize BRCircularProgressView

    let progressView = BRCircularProgressView(frame: CGRect(x: 100, y: 100, width: 50, height: 50))
    progressView.setCircleStrokeWidth(5)
    progressView.setCircleStrokeColor(UIColor.lightGray, circleFillColor: UIColor.white, progressCircleStrokeColor: UIColor.blue, progressCircleFillColor: UIColor(red: 0, green: 0, blue: 0, alpha: 0.3))
    progressView.setProgressTextFont(UIFont.systemFont(ofSize: 17), color: UIColor.green)
    progressView.setProgressText("50")

# Description

This control can be used for multi purpose like:
* Showing download progress,
* Showing upload progress,
* Showing timer with an interval.

And this is fully configurable, you can set the different color of each part of the progress. Customize your progress bar with
* circleStrokeColor,
* circleFillColor,
* progressCircleStrokeColor,
* progressCircleFillColor.

![Alt text](https://github.com/BrammanandSoni/BRCircularProgressBar/blob/master/BRCircularProgressBar/info.png)
