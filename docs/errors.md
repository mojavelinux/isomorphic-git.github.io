---
title: Error Codes
sidebar_label: Error Code Index
---

<aside>
Right now this merely lists the possible error messages, so it's of little practical value.
However I would like it to become a useful page that expands on the short error message with a detailed
explanation, and gives possible resolutions to common scenarios where these errors occur.
</aside>

### AcquireLockFileFail
Unable to acquire lockfile "{ filename }". Exhausted tries.

### AddingRemoteWouldOverwrite
Adding remote { remote } would overwrite the existing remote. Use "force: true" to override.

### AmbiguousShortOid
Found multiple oids matching "{ short }" ({ matches }). Use a longer abbreviation length to disambiguate them.

### AssertServerResponseFail
Expected "{ expected }" but got "{ actual }".

### BranchDeleteError
Failed to delete branch "{ ref }" because branch "{ ref }" checked out now.

### CommitNotFetchedError
Failed to checkout "{ ref }" because commit { oid } is not available locally. Do a git fetch to make the branch available locally.

### CoreNotFound
No plugin core with the name "{ core }" is registered.

### CorruptShallowOidFail
non-40 character shallow oid: { oid }

### DirectoryIsAFileError
Unable to read "{ oid }:{ filepath }" because encountered a file where a directory was expected.

### DirectorySeparatorsError
"filepath" parameter should not include leading or trailing directory separators because these can cause problems on some platforms

### DoubleReleaseLockFileFail
Cannot double-release lockfile "{ filename }".

### EmptyServerResponseFail
Empty response from git server.

### ExpandRefError
Could not expand reference "{ ref }".

### FastForwardFail
A simple fast-forward merge was not possible.

### FileReadError
Could not read file "{ filepath }".

### GitRootNotFoundError
Unable to find git root for { filepath }.

### HTTPError
HTTP Error: { statusCode } { statusMessage }

### InternalFail
An internal error caused this command to fail. Please file a bug report at https://github.com/isomorphic-git/isomorphic-git/issues with this error message: { message }

### InvalidDepthParameterError
Invalid value for depth parameter: { depth }

### InvalidRefNameError
Failed to { verb } { noun } "{ ref }" because that name would not be a valid git reference. A valid alternative would be "{ suggestion }".

### MaxSearchDepthExceeded
Maximum search depth of { depth } exceeded.

### MergeNotSupportedFail
Non-fast-forward merges are not supported yet.

### MissingAuthorError
Author name and email must be specified as an argument or in the .git/config file.

### MissingPasswordTokenError
Missing password or token

### MissingRequiredParameterError
The function "{ function }" requires a "{ parameter }" parameter but none was provided.

### MissingTokenError
Missing token

### MissingUsernameError
Missing username

### MixPasswordOauth2formatMissingTokenError
Cannot mix "password" with "oauth2format". Missing token.

### MixPasswordOauth2formatTokenError
Cannot mix "password" with "oauth2format" and "token"

### MixPasswordTokenError
Cannot mix "password" with "token"

### MixUsernameOauth2formatMissingTokenError
Cannot mix "username" with "oauth2format". Missing token.

### MixUsernameOauth2formatTokenError
Cannot mix "username" with "oauth2format" and "token"

### MixUsernamePasswordOauth2formatMissingTokenError
Cannot mix "username" and "password" with "oauth2format". Missing token.

### MixUsernamePasswordOauth2formatTokenError
Cannot mix "username" and "password" with "oauth2format" and "token"

### MixUsernamePasswordTokenError
Cannot mix "username" and "password" with "token"

### NoHeadCommitError
Failed to create { noun } "{ ref }" because the HEAD ref could not be resolved to a commit.

### NoRefspecConfiguredError
Could not find a fetch refspec for remote "{ remote }".\\nMake sure the config file has an entry like the following:\\n[remote "{ remote }"]\\nfetch = +refs/heads/*:refs/remotes/origin/*

### NotAnOidFail
Expected a 40-char hex object id but saw "{ value }".

### NotImplementedFail
TODO: { thing } still needs to be implemented!

### ObjectTypeAssertionFail
Object { oid } was anticipated to be a { expected } but it is a { type }. This is probably a bug deep in isomorphic-git!

### ObjectTypeAssertionInPathFail
Found a blob { oid } in the path "{ path }" where a tree was expected.

### ObjectTypeAssertionInRefFail
{ ref } is not pointing to a "commit" object but a "{ type }" object.

### ObjectTypeAssertionInTreeFail
Object { oid } in tree for "{ entrypath }" was an unexpected object type "{ type }".

### ObjectTypeUnknownFail
Object { oid } has unknown type "{ type }".

### PluginSchemaViolation
Schema check failed for "{ plugin }" plugin; missing { method } method.

### PluginUndefined
A command required the "{ plugin }" plugin but it was undefined.

### PluginUnrecognized
Unrecognized plugin type "{ plugin }"

### PushRejectedNonFastForward
Push rejected because it was not a simple fast-forward. Use "force: true" to override.

### PushRejectedTagExists
Push rejected because tag already exists. Use "force: true" to override.

### ReadObjectFail
Failed to read git object with oid { oid }

### RefExistsError
Failed to create { noun } "{ ref }" because { noun } "{ ref }" already exists.

### RefNotExistsError
Failed to { verb } { noun } "{ ref }" because { noun } "{ ref }" does not exists.

### RemoteDoesNotSupportDeepenNotFail
Remote does not support shallow fetches excluding commits reachable by refs.

### RemoteDoesNotSupportDeepenRelativeFail
Remote does not support shallow fetches relative to the current shallow depth.

### RemoteDoesNotSupportDeepenSinceFail
Remote does not support shallow fetches by date.

### RemoteDoesNotSupportShallowFail
Remote does not support shallow fetches.

### RemoteDoesNotSupportSmartHTTP
Remote does not support the "smart" HTTP protocol, and isomorphic-git does not support the "dumb" HTTP protocol, so they are incompatible.

### RemoteUrlParseError
Cannot parse remote URL: "{ url }"

### ResolveCommitError
Could not resolve { oid } to a commit.

### ResolveRefError
Could not resolve reference "{ ref }".

### ResolveTreeError
Could not resolve { oid } to a tree.

### ShortOidNotFound
Could not find an object matching "{ short }"

### TreeOrBlobNotFoundError
No file or directory found at "{ oid }:{ filepath }".

### UnknownOauth2Format
I do not know how { company } expects its Basic Auth headers to be formatted for OAuth2 usage. If you do, you can use the regular username and password parameters to set the basic auth header yourself.

### UnknownTransportError
Git remote "{ url }" uses an unrecognized transport protocol: "{ transport }"

### UnparseableServerResponseFail
Unparsable response from server! Expected "unpack ok" or "unpack [error message]" but received "{ line }".

