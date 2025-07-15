# Hide YouTube Shorts & Instagram Reels

A [uBlock Origin](https://github.com/gorhill/uBlock) filter list to hide all traces of YouTube Shorts and Instagram Reels.

This filter list is optimized for mobile and desktop views of YouTube and Instagram. It removes Shorts sections, buttons, and thumbnails from YouTube (especially [m.youtube.com](https://m.youtube.com)) and also filters out Reels entries from Instagram’s sidebar.

The filters may work with other content blockers, but they have primarily been tested with uBlock Origin.

## How to Use

1. Copy and paste the following link into uBlock Origin:
   - [https://github.com/MrXTheAnon/ublock-hide-yt-shorts/blob/master/list.txt](https://github.com/MrXTheAnon/ublock-hide-yt-shorts/blob/master/list.txt)
2. Open **uBlock Origin → Dashboard → Filter Lists**.
3. Scroll to the **"Import..."** section and paste the link.
4. Click **Apply Changes**.

## Features

- Removes **YouTube Shorts**:
  - From homepage, search results, channel pages, and bottom nav (on mobile).
- Removes **Instagram Reels**:
  - Hides the Reels icon and its container from the sidebar (mobile & desktop).
  - *(Optional – Desktop Only)* You can also hide the **Instagram Explore** icon by uncommenting a specific filter.
  - **Note:** On **mobile**, Instagram merges Explore and Search into a single icon. Hiding Explore on mobile will also hide the Search button.
  - This filter is **commented out by default** in the list. You may **uncomment it** if you're using Instagram primarily on desktop and want Explore hidden.

## License

See [LICENSE.md](https://github.com/MrXTheAnon/ublock-hide-yt-shorts/blob/master/LICENSE.md)

