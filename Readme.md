# Todo
 * Revamp menu: Can take whole screen and disappear during drafting, (add a button to have it reappear?)
 * Optimize DLScryfallCards.py; Use MTGA data as base for cards and ids
 * Add back ready to draft... "I'm ready!" ? All it does is signaling the session owner that you're here and ready; a button on the right of SessionID ?
 * Display foils as... foils in front end?
 * Make chrono more visible (especially when < 10)
 * Add options for draft log: ["Send to everybody", "Send to owner only", "Do not send"]
 * Draft log: Add table order and drafted colors to draft log (see Vincent H. feedback)
 * -----
 * Move pick time out to server side?
 * Multiple prevention is only done by ID, maybe we should check the card name?
 * (I finally found out about socket.io room feature... I should use that instead of manually handling sessions.)
 
# Check
 * Check possible rare duplication? (check randomness of packs)
 * ----
 * Add notification option: In a sub menu add a way to activate notifications (HTML5 Notification?) fired when a draft is launched.
 * Make chat message easier to read
 * Set Multiple Selection
 * Player limit
 * Rarity selection
 * Prevent multiple copies of the same card in a single booster
 * Add a sideboard option (rename "Your Cards" to "Deck" and move what's currently the deck bellow and rename it to "Sideboard". Update exported to support the sideboard)
 
# Bugs
 * Player list messed during draft (triggered by a disconnect? - maybe by a quick disconnect/reconnect)
 * Guildgates won't import in arena : Guildgates do not have localized names 