# MBX Flow

MBX Flow is a social media publishing tool for artists and labels. This extension connects Gemini CLI to one MBX Flow workspace.

## What you can do
- `get_workspace`, `list_accounts`: see the workspace and its connected social accounts.
- `list_posts`, `get_post`: read drafts and scheduled posts.
- `create_draft`, `schedule_post`: write a draft or schedule a post at least 10 minutes ahead.
- `search_photos`: find a free stock photo for a post.
- `get_photo_upload_link`: give the person a link to add their own photo to a post.

## Rules
- This connection never publishes right away and never deletes. Publishing now stays with a person inside MBX Flow.
- Always confirm the accounts, the text and the date with the person before calling `schedule_post`.
