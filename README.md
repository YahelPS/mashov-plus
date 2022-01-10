
<img src="src/assets/img/icon-128.png" width="64"/>

# Features
Since Mashov Plus is a new extension, it currently does not have a lot of features.
Feel free to suggest features [here](https://forms.gle/CSs5JDaYepzwhXhT6).
 - Grades avg. for each month/semester
 - Blur user avatar
 
 **More are on their way!**

# Development
Feel free to submit [pull requests](https://docs.github.com/en/pull-requests/collaborating-with-pull-requests/proposing-changes-to-your-work-with-pull-requests/about-pull-requests) if you found any bug, added any feature, or just want to make the structure better!

## Instuctions
Fiorst, you have to download the code in order to edit it, by running the following command:

    git clone https://github.com/YahelPS/mashov-plus
Then, go to the reposotory's directori and run the following command to install the required dependencies.

    npm i
Or, if you  prefer using yarn:

    yarn install


Then, modify `utils/env.js` and change the `ENV` variable to `"DEVELOPMENT"`

After you've done all of the above, you need to run one of these to build the extension.

    npm run build
Or

    yarn build

After the build was finished, go to [chrome://extensions](chrome://extensions) and make sure that Developer Mode is enabled.
Now, simply click <kbd>Load Unpacked</kbd>, then run

    npm run start
Or

    yarn start

And when you're done submit a pull request with your edit!
