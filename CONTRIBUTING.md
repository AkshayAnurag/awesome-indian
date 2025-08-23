Found an amazing Indian app that should be featured here? It can be open-source as well as closed source. Feel free to contribute!

### How to add an app

1. Fork this repository
2. Add app details to the appropriate table with the following details:
    - **Category**: Choose from one of the existing categories or suggest a new one
    - **Name**: Name of the application
    - **Description**: Official description from the GitHub repository or app store. Keep it brief
    - **Contribute**:
        - Link to the Source code repository (if open source). **Supported**: GitHub, Gitlab, Codeberg, Gitea
        - For **GitHub**, use the following HTML:

                <td style="text-align: center">
                    <a
                        href="<LINK TO THE REPOSITORY>"
                        target="_blank"
                        rel="noopener noreferrer"
                    >
                        <img
                            src="https://img.shields.io/github/stars/<USER NAME>/Linkora?style=plastic&amp;logo=github&amp;logoColor=181717&amp;labelColor=white"
                            alt="GitHub Repo stars"
                        />
                        <img
                            src="https://img.shields.io/github/contributors/<USER NAME>/<REPO NAME>?style=plastic&amp;logo=github&amp;logoColor=181717&amp;labelColor=white"
                            alt="GitHub contributors"
                        />
                        <img
                            src="https://img.shields.io/github/issues/<USER NAME>/<REPO NAME>?style=plastic&amp;logo=github&amp;logoColor=181717&amp;labelColor=white"
                            alt="GitHub Issues"
                        />
                    </a>
                </td>
        - For **Gitlab**, use the following HTML:

                <td style="text-align: center">
                    <a
                        href="<LINK TO THE REPOSITORY>"
                        target="_blank"
                        rel="noopener noreferrer"
                    >
                        <img
                            src="https://img.shields.io/gitlab/stars/<GITLAB PROJECT PATH>?style=plastic&logo=gitlab&logoColor=FC6D26&labelColor=white"
                            alt="GitLab Stars"
                        />
                        <img
                            src="https://img.shields.io/gitlab/contributors/<GITLAB PROJECT PATH>?style=plastic&logo=gitlab&logoColor=FC6D26&labelColor=white"
                            alt="GitLab contributors"
                        />
                        <img
                            src="https://img.shields.io/gitlab/issues/open/<GITLAB PROJECT PATH>?style=plastic&logo=gitlab&logoColor=FC6D26&labelColor=white"
                            alt="GitLab Issues"
                        />
                    </a>
                </td>
        - For **Codeberg**, use the following HTML:

                <td style="text-align: center">
                    <a
                        href="<LINK TO THE REPOSITORY>"
                        target="_blank"
                        rel="noopener noreferrer"
                    >
                        <img
                            src="https://img.shields.io/gitea/stars/<USER NAME>/<REPO NAME>?gitea_url=https%3A%2F%2Fcodeberg.org%2F&style=plastic&logo=codeberg&logoColor=2185D0&labelColor=white"
                            alt="Codeberg Stars"
                        />
                        <img
                            src="https://img.shields.io/gitea/issues/open/<USER NAME>/<REPO NAME>?gitea_url=https%3A%2F%2Fcodeberg.org%2F&style=plastic&logo=codeberg&logoColor=2185D0&labelColor=white"
                            alt="Codeberg Issues"
                        />
                    </a>
                </td>
        - For **Gitea**, use the following HTML:

                <td style="text-align: center">
                    <a
                        href="<LINK TO THE REPOSITORY>"
                        target="_blank"
                        rel="noopener noreferrer"
                    >
                        <img
                            src="https://img.shields.io/gitea/stars/<USER NAME>/<REPO NAME>?style=plastic&logo=gitea&logoColor=609926&labelColor=white"
                            alt="Gitea Stars"
                        />
                        <img
                            src="https://img.shields.io/gitea/issues/open/<USER NAME>/<REPO NAME>?style=plastic&logo=gitea&logoColor=609926&labelColor=white"
                            alt="Gitea Issues"
                        />
                    </a>
                </td>
        - These are [Shields.io](https://shields.io) badges which fetch the latest stars on the repo, contributors count and number of issues. (No contributor count in case of Gitea/Codeberg)
        - Feel free to add badges for more than one platform, e.g. if a user has the same repository on GitHub and Gitlab, feel free to add both.
        - The reason to include these details is to encourage the visitor to engage with the repository. (*We strongly believe that the Indian tech community has a lot of talented individuals who can have a lot of impact. All we need is a bit of encouragement!*)
    - **Community**:
        - Links to communities run by the author/company. **Supported**: Discord, Telegram, Reddit
        - For Discord servers, use the following HTML:

                <td style="text-align: center">
                    <a
                        href="<LINK TO THE DISCORD SERVER>"
                        target="_blank"
                        rel="noopener noreferrer"
                    >
                        <img
                            src="https://img.shields.io/discord/<DISCORD SERVER ID>?style=plastic&logo=discord&logoColor=5865F2&label=Discord&labelColor=white"
                            alt="Discord"
                        />
                    </a>
                </td>
            - **Required**: You need the Discord server ID in order to create the above [Shields.io](https://shields.io) badge. (*[Read this](https://shields.io/badges/discord) for instructions on how to get the server ID*)
        - For Telegram channels/groups, use the following HTML:

                <td style="text-align: center">
                    <a
                        href="<LINK TO THE TELEGRAM CHANNEL/GROUP>"
                        target="_blank"
                        rel="noopener noreferrer"
                    >
                        <img
                            src="https://img.shields.io/badge/Join-26A5E4?style=plastic&logo=telegram&logoColor=26A5E4&labelColor=white"
                            alt="Telegram"
                        />
                    </a>
                </td>
        - For Reddit subreddit, use the following HTML:

                <td style="text-align: center">
                    <a
                        href="<LINK TO THE SUBREDDIT>"
                        target="_blank"
                        rel="noopener noreferrer"
                    >
                        <img
                            src="assets/images/reddit.png"
                            alt="Reddit"
                            height="30"
                        />
                    </a>
                </td>
    - **Download**:
        - Link to the download plaform
        - Supported:
            - **Android**: F-Droid (preferred for open-source), IzzyOnDroid, GitHub, Play Store
                - For F-Droid, use the following HTML:
                
                        <a
                            href="<LINK TO FDROID PACKAGE>"
                            target="_blank"
                            rel="noopener noreferrer"
                        >
                            <img
                                src="assets/images/get-it-on-fdroid.png"
                                alt="Get it on F-Droid"
                                height="60"
                            />
                        </a>
                - For IzzyOnDroid, use the following HTML:
                
                        <a
                            href="<LINK TO IZZYONDROID PACKAGE>"
                            target="_blank"
                            rel="noopener noreferrer"
                        >
                            <img
                                src="assets/images/get-it-on-izzyondroid.png"
                                alt="Get it on IzzyOnDroid"
                                height="60"
                            />
                        </a>
                - For GitHub, use the following HTML:

                        <a
                            href="<LINK TO GITHUB RELEASES PAGE>"
                            target="_blank"
                            rel="noopener noreferrer"
                        >
                            <img
                                src="assets/images/get-it-on-github.png"
                                alt="Get it on GitHub"
                                height="60"
                            />
                        </a>
                - For Google Play, use the following HTML:

                        <a
                            href="<LINK TO PLAY STORE PACKAGE>"
                            target="_blank"
                            rel="noopener noreferrer"
                        >
                            <img
                                src="assets/images/get-it-on-play.png"
                                alt="Get it on Google Play"
                                height="60"
                            />
                        </a>
        - Feel free to add links for more than one download platform
3. Submit a Pull Request

#### **NOTE**: Please <ins>DO NOT</ins> change the style of any of the HTML tags. All rows should follow the same general style.

### Submission Guidelines
- Owner of the repository/publisher of the app should be an **Indian developer or Indian company**
- Feel free to start a new issue if you think that we need to support other platforms
