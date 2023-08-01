# QA Full-Stack Developer Challenge

This challenge consists in incremental steps to build a simple full-stack application (do the steps in order).

## Back-end

For the back-end, implement the following steps:

1. Set-up an API in any web framework (suggested: Flask / FastAPI)

2. Add a `/list` endpoint returning the data in /server/db/list.json in the following format:

```json
{"images": [
  ["id0", "name0", "url0", ["tag1", "tag2"]],
  ["id1", "name1", "url1", ["tag1", "tag2"]]
  ...
  ["idN", "nameN", "urlN", ["tag1", "tag2"]]
]}
```

3. Convert the list.json file to any proper database (e.g. SQLite or be creative), and make the `/list` endpoint read from there.

4. Create a `/edit/<image_id>` endpoint to edit the tags of a certain image

## Front-end

1. Set-up a front-end application in your framework of choice (React highly preferred)

2. With the data returned from the server `/list` endpoint implement an image gallery in the client folder

3. Create a filter functionality that let the user filter the images by name and tag

4. Implement the possibility to filter by multiple tags at the same time

5. Function to add new tags to the images (just the front-end side for now)

6. Implement step 5 on the server (NOTE: to implement this step you need to implement step 4 of the server-side)

## Submission

Your work should be uploaded into a personal repository on GitHub or GitLab and sent to hr@quickalgorithm.com.

For any further queries feel free to get in touch with us.
