**STRUCT**

# `GitHubPR`

```swift
public struct GitHubPR: Decodable, Equatable
```

## Properties
### `number`

```swift
public let number: Int
```

> The number of the pull request.

### `title`

```swift
public let title: String
```

> The title of the pull request.

### `body`

```swift
public let body: String
```

> The markdown body message of the pull request.

### `user`

```swift
public let user: GitHubUser
```

> The user who submitted the pull request.

### `assignee`

```swift
public let assignee: GitHubUser?
```

> The user who is assigned to the pull request.

### `assignees`

```swift
public let assignees: [GitHubUser]?
```

> The users who are assigned to the pull request.

### `createdAt`

```swift
public let createdAt: Date
```

> The ISO8601 date string for when the pull request was created.

### `updatedAt`

```swift
public let updatedAt: Date
```

> The ISO8601 date string for when the pull request was updated.

### `closedAt`

```swift
public let closedAt: Date?
```

> The ISO8601 date string for when the pull request was closed.

### `mergedAt`

```swift
public let mergedAt: Date?
```

> The ISO8601 date string for when the pull request was merged.

### `head`

```swift
public let head: GitHubMergeRef
```

> The merge reference for the _other_ repo.

### `base`

```swift
public let base: GitHubMergeRef
```

> The merge reference for _this_ repo.

### `state`

```swift
public let state: PullRequestState
```

> The state for the pull request: open, closed, locked, merged.

### `isLocked`

```swift
public let isLocked: Bool
```

> A boolean indicating if the pull request has been locked to contributors only.

### `isMerged`

```swift
public let isMerged: Bool?
```

> A boolean indicating if the pull request has been merged.

### `commitCount`

```swift
public let commitCount: Int?
```

> The number of commits in the pull request.

### `commentCount`

```swift
public let commentCount: Int?
```

> The number of comments in the pull request.

### `reviewCommentCount`

```swift
public let reviewCommentCount: Int?
```

> The number of review-specific comments in the pull request.

### `additions`

```swift
public let additions: Int?
```

> The number of added lines in the pull request.

### `deletions`

```swift
public let deletions: Int?
```

> The number of deleted lines in the pull request.

### `changedFiles`

```swift
public let changedFiles: Int?
```

> The number of files changed in the pull request.

### `milestone`

```swift
public let milestone: GitHubMilestone?
```

> The milestone of the pull request

### `htmlUrl`

```swift
public let htmlUrl: String
```

> The link back to this PR as user-facing
