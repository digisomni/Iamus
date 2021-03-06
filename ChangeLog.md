# Iamus Changelog
## Version 2.3.6

<ul>
<li><a href="http://github.com/vircadia/Iamus/commit/d39b5731e0481cc0006dae2e6fb4a8530137b0bb">view &bull;</a> Update ChangeLog.md</li> 
<li><a href="http://github.com/vircadia/Iamus/commit/c67706945d71c51d806023c02dce26d4147ea1a6">view &bull;</a> Minor bug fixes in BackupDb.sh</li> 
<li><a href="http://github.com/vircadia/Iamus/commit/6b05304c326f8303a18afbde9421ccf030949297">view &bull;</a> Update links and names (#66)</li> 
<li><a href="http://github.com/vircadia/Iamus/commit/cc8e9d64f077c2ee62405cfe2437ad3483845c24">view &bull;</a> Update NPM package version.</li> 
<li><a href="http://github.com/vircadia/Iamus/commit/8cf1eee04aab3a069442c346241cf96aa8572f1a">view &bull;</a> Fix problem where user wasn't returned their token by /api/v1/tokens     The search field must be specified to AccountScopeFilter     A few other places were checked and updated.</li> 
<li><a href="http://github.com/vircadia/Iamus/commit/1d0be3bf637315c3196390124600cada3fc218f1">view &bull;</a> Bump version to 2.3.6</li> 
</ul>

## Version 2.3.5

<ul>
<li><a href="http://github.com/vircadia/Iamus/commit/e95291d4988f48d780795e134a364d9120f22fc3">view &bull;</a> Update ChangeLog.md</li> 
<li><a href="http://github.com/vircadia/Iamus/commit/b360944a70a994ee701a0f2b23303a1d71dd76fb">view &bull;</a> Change Place filter 'maturity' to take a comma separated string     of maturity classes to match.</li> 
<li><a href="http://github.com/vircadia/Iamus/commit/00355c7481b1958379d574a1ff7acc65a18d2eed">view &bull;</a> When creating a Place, default maturity to the parent domain's maturity. Default DomainEntity.maturity to Maturity.UNRATED.</li> 
<li><a href="http://github.com/vircadia/Iamus/commit/a80864dfea02c284c195000184392f9c1f7bdcce">view &bull;</a> Massive refactoring to remove circular import dependencies that were     causing null value initializations due to how Javascript loads. Move Entity field definitions into separate files. Moved Entity field getting and setting into the Entity controlling class. Repackaged (into multiple files) Permission and Get/Set/Validate routines.</li> 
<li><a href="http://github.com/vircadia/Iamus/commit/bf4df1bad8290c7ef4b20e5ce940b1a925f3b04e">view &bull;</a> Bump version to 2.3.5</li> 
</ul>

## Version 2.3.4

<ul>
<li><a href="http://github.com/vircadia/Iamus/commit/387e26b76f6c98b5fe5e55f34d319c588f77b5a8">view &bull;</a> Update Changelog.md</li> 
<li><a href="http://github.com/vircadia/Iamus/commit/d9759a3986c7c906b687047df268a9476193648d">view &bull;</a> Add documentation on the design of the Entity field get/set system.</li> 
<li><a href="http://github.com/vircadia/Iamus/commit/356b27369300f543e57dd7e7a73bc8f1d686ea15">view &bull;</a> Fix DELETE Place so the owner of the Place's domain can delete the Place.</li> 
<li><a href="http://github.com/vircadia/Iamus/commit/f9651d25d43a76d8e4aa5ee932f3e0a0f279514a">view &bull;</a> Make Monitoring.event so it doesn't fail if monitoring was not inited.</li> 
<li><a href="http://github.com/vircadia/Iamus/commit/d45833f889f838bdefe5cf8bfb31d316aad486e5">view &bull;</a> Record network_address and network_port if specified when creating doamin.</li> 
<li><a href="http://github.com/vircadia/Iamus/commit/acaa36a494ad439122f48376ba31f08068219566">view &bull;</a> Added "maturity" and "tags" to PlaceEntity Centralized "maturity" specifications into src/Entities/sets/Maturity.ts Moved AccountAvailability and AccountRoles to src/Entities/sets and made a set pattern. Documented "/api/v1/places?maturity=LEVEL" and "/api/v1/places?tags=TAGLIST" Added comments to src/Entities/EntityFilters/CriteriaFilter.ts explaining how filters are to be used Added "maturity-catagories" to Places responses Fixed /api/v1/users/places to return only the places that belong to the requesting user Deleted bin/www -- what was that from??</li> 
<li><a href="http://github.com/vircadia/Iamus/commit/56c4649b60f58915c3b05907f3f1149cf3fe0e71">view &bull;</a> Bump version to 2.3.4</li> 
</ul>

## Version 2.3.3

<ul>
<li><a href="http://github.com/vircadia/Iamus/commit/fe0518f44cbbab7e87a68c8e2bf44a8149cf9262">view &bull;</a> Update Changelog.md</li> 
<li><a href="http://github.com/vircadia/Iamus/commit/f1299154d43fe10687de6bc8ee79460fa4e24e53">view &bull;</a> Add proper handling of SIGTERM and SIGINT     Shutdown server, finish requests, and then cleanly exit.</li> 
<li><a href="http://github.com/vircadia/Iamus/commit/6a8c2b0fab15558ef684555ff35843d030dcf718">view &bull;</a> Add domain.sponsorAccountId to Places information returned by /api/v1/places/... Update documentation.</li> 
<li><a href="http://github.com/vircadia/Iamus/commit/fc4f64670e5836f732b8cef1f5a5a477d3aea76f">view &bull;</a> Fix problem with changing username: update AccountEntity setPermissions. Should fix vircadia/project-iamus-dashboard#21</li> 
<li><a href="http://github.com/vircadia/Iamus/commit/8cf02628b3c8055d0e84655fa2e65951bd2a6a4b">view &bull;</a> Bump version to 2.3.3</li> 
</ul>

## Version 2.3.2

<ul>
<li><a href="http://github.com/vircadia/Iamus/commit/1a137f8f7b2722234ef5d3a5fd110d1007a502fd">view &bull;</a> Fix sorting of versions in genChangeLog.sh Update Changelog.md</li> 
<li><a href="http://github.com/vircadia/Iamus/commit/4654f30bb6af0cb89ac0a4c7fcf9f640576876f3">view &bull;</a> Return more useful error message when finding a domain name contains     non-allowed characters. Some non-functional formatting and code cleanup.</li> 
<li><a href="http://github.com/vircadia/Iamus/commit/729cdd156c95d514751a7663bafd6b584c725d49">view &bull;</a> Fix line endings to Linux style</li> 
<li><a href="http://github.com/vircadia/Iamus/commit/0511c01854bebf75a46a7ad79dbf243f194aa06d">view &bull;</a> Modify Entity field value validation to return reason for any validation failure.     Rather than just returning 'false', the validator returns a structure with         an optional reason for the validation failure. Modify the callers of Entity field setting to return error. Closes #48 Fix AccountEntity.Availability and AccountEntity.Roles to validate values correctly.</li> 
<li><a href="http://github.com/vircadia/Iamus/commit/8dca92378f89629819e544ff3d73351756902b2e">view &bull;</a> Tone down the AccountEntity.email format validation to require one AT sign     An RFC complient email address can be very complex so rely on later     email verification handshake to really checkout that email is a good format. Closes #63</li> 
<li><a href="http://github.com/vircadia/Iamus/commit/3d6f7679ea605c288f537ddf8fffd011d9795922">view &bull;</a> Bump version to 2.3.2</li> 
</ul>

## Version 2.3.1

<ul>
<li><a href="http://github.com/vircadia/Iamus/commit/a0edba9f67e250ba5d1b8ad5c758bd17d4981af3">view &bull;</a> Update ChangeLog.md</li> 
<li><a href="http://github.com/vircadia/Iamus/commit/ffe9c154e709e5138c3afaa7377b448abac81354">view &bull;</a> Bump version to 2.3.1</li> 
</ul>

## Version 2.2.24

<ul>
<li><a href="http://github.com/vircadia/Iamus/commit/f59619261cfa874be2c3cd5f436def099040dde8">view &bull;</a> Update Changelog.md</li> 
<li><a href="http://github.com/vircadia/Iamus/commit/7ec03825c70af2f85ff569c38a59a0c77dca242c">view &bull;</a> When deleting connections or friends, remove the reverse pointers:     Deleting a connection removes both connection and friend in both accounts.     Deleting a friend removes friend from other account also. Closes #59</li> 
<li><a href="http://github.com/vircadia/Iamus/commit/c0ca649c6b97915662597363785cf3ceeae85d2e">view &bull;</a> For domain token generation default web page, move generated domain     token text up higher and make it white so it stands out. Clean up some CSS errors. Closes #5</li> 
<li><a href="http://github.com/vircadia/Iamus/commit/53ac8b06c950adeab17901476c2054c68315e49b">view &bull;</a> Bump version to 2.2.24</li> 
</ul>

## Version 2.2.23

<ul>
<li><a href="http://github.com/vircadia/Iamus/commit/1c51ba8f46832f70551d2802422cbb91c20a681d">view &bull;</a> Update ChangeLog.md Modify genChangelog.sh to get the tags from git and generating a list     of the last 10 version tags (tag form: major.minor.patch)</li> 
<li><a href="http://github.com/vircadia/Iamus/commit/db36bccf9dd965cc66940ff839596249d94abe14">view &bull;</a> Add pagination response fields to API requests that handle pagination.</li> 
<li><a href="http://github.com/vircadia/Iamus/commit/2b01b6bad64d0a7ceeb141befd5f6b0fb41db198">view &bull;</a> Implement redirection of /users/:username to Dashboard. Closes #58</li> 
<li><a href="http://github.com/vircadia/Iamus/commit/4dcab7bbcbf4bf5bb2f02143c541fe88b9abe3ac">view &bull;</a> Bump version to 2.2.23</li> 
</ul>

## Version 2.2.22

<ul>
<li><a href="http://github.com/vircadia/Iamus/commit/9e98dc82bb0fab9ae2b0ffa3e58111de024ba1cb">view &bull;</a> Update ChangeLog.md</li> 
<li><a href="http://github.com/vircadia/Iamus/commit/650824f948c3d905ebc2242147d32364b0170914">view &bull;</a> Remove the one-time, DB fix for bad domain network addresses.</li> 
<li><a href="http://github.com/vircadia/Iamus/commit/4e81b42308fb55b78d6b6a4fd625d0f9917b0ed7">view &bull;</a> Add 'BRANCH' argument to Dockerfile for optional branch building</li> 
<li><a href="http://github.com/vircadia/Iamus/commit/cfdaf535927a3d02a03d547fa7e7c24284bd9ddd">view &bull;</a> Modify the connection building code for /api/v1/users/connections.</li> 
<li><a href="http://github.com/vircadia/Iamus/commit/e4a58caca81fbd274e919591c219ddcc508baf01">view &bull;</a> Correct 'location' element name in /api/v1/users/connections. Add documentation for /api/v1/users/connections</li> 
<li><a href="http://github.com/vircadia/Iamus/commit/44a371d26d2564308e2654c9db9318291da6fea6">view &bull;</a> Add pagination response fields to /api/v1/users/connections. Add response field function to other criteria filters.</li> 
<li><a href="http://github.com/vircadia/Iamus/commit/292681ac5e7e41dbdb0451714eaca27e9bbc663f">view &bull;</a> Implement POST /api/v1/user/friends so a user can make a connection into a friend.</li> 
<li><a href="http://github.com/vircadia/Iamus/commit/b3776e16c969bf5328dbb7f524d0c845166d5cdb">view &bull;</a> Allow an account to add any connection or friend they wish</li> 
<li><a href="http://github.com/vircadia/Iamus/commit/24c9c956fffd1db523f9f232ec42c3dbb0f69144">view &bull;</a> Change /api/v1/users/connections response to have proper connection type flag.     The code seemed to want "is_friend" but it really wants just "friend". Update documentation for /api/v1/users/connections</li> 
<li><a href="http://github.com/vircadia/Iamus/commit/8ddfdab9df65206edfb927ba25b7fe3c939088c5">view &bull;</a> Bump version to 2.2.22</li> 
</ul>

