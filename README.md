# Ubo

troubleshoot info

uBlock Origin: 1.60.0
Firefox: 131
filterset (summary):
 network: 151291
 cosmetic: 48484
 scriptlet: 21177
 html: 2027
listset (total-discarded, last-updated):
 default:
  user-filters: 4-0, never
  ublock-filters: 40644-130, 38m Δ
  ublock-badware: 11581-6, 38m Δ
  ublock-privacy: 1283-22, 38m Δ
  ublock-unbreak: 2535-1, 38m Δ
  ublock-quick-fixes: 171-10, 38m Δ
  easylist: 85859-187, 38m Δ
  easyprivacy: 53140-62, 38m Δ
  urlhaus-1: 25780-0, now
  plowe-0: 3541-992, now
filterset (user): [array of 4 redacted]
userSettings: [none]
hiddenSettings: [none]
supportStats:
 allReadyAfter: 2132 ms
 maxAssetCacheWait: 18 ms
 cacheBackend: indexedDB
popupPanel:
 blocked: 194
 network:
  youtube.com: 107
  doubleclick.net: 5
  google.com: 82
 extended:
  ##.ytp-featured-product
  ###player-ads
  ##.ytp-suggested-action > button.ytp-suggested-action-badge
  ##+js(set-constant, ytInitialPlayerResponse.playerAds, undefined…
  ##+js(set-constant, ytInitialPlayerResponse.adPlacements, undefi…
  ##+js(set-constant, ytInitialPlayerResponse.adSlots, undefined)
  ##+js(set-constant, playerResponse.adPlacements, undefined)
  ##+js(json-prune-fetch-response, playerAds adPlacements adSlots …
  ##+js(json-prune-fetch-response, reelWatchSequenceResponse.entri…
  ##+js(trusted-replace-node-text, script, (function serverContrac…
  ##+js(adjust-setTimeout, [native code], 17000, 0.001)
  ##+js(json-prune-xhr-response, playerAds adPlacements adSlots pl…
  ##+js(set-constant, yt.config_.EXPERIMENT_FLAGS.web_bind_fetch, …
  ##+js(adjust-setTimeout, resolve(1), *, 0.001)
  ##+js(set-constant, yt.config_.EXPERIMENT_FLAGS.web_enable_ab_rs…
  ##+js(set-constant, yt.config_.EXPERIMENT_FLAGS.ab_pl_man, false…
