# ZyroX-CV2-AIO-With-Dashboard - Complete Repository Manifest

> **Total Files:** 967 files | **Lines of Code:** 60,706 lines | **Stack:** Python 3.10+ (discord.py, FastAPI), Next.js 14, Tailwind CSS

Downloadable Archive with all fixes applied: `ZyroX-CV2-AIO-With-Dashboard-fixed.zip` (available in this workspace).

---

## 📁 Core Bot Entry & Configuration

- `bot/CodeX.py`
- `bot/config.yml`
- `bot/requirements.txt`
- `bot/LICENSE`

## 📁 Bot Core Architecture

- `bot/core/Cog.py`
- `bot/core/Context.py`
- `bot/core/__init__.py`
- `bot/core/zyrox.py`

## 📁 FastAPI Dashboard Backend (REST API)

- `bot/api/__init__.py`
- `bot/api/db_manager.py`
- `bot/api/dependencies.py`
- `bot/api/schemas.py`
- `bot/api/server.py`
- `bot/api/routes/__init__.py`
- `bot/api/routes/admin.py`
- `bot/api/routes/bot.py`
- `bot/api/routes/guilds.py`

## 📁 Bot Commands (Cogs)

- `bot/cogs/commands/Birthday.py`
- `bot/cogs/commands/Embed.py`
- `bot/cogs/commands/Games.py`
- `bot/cogs/commands/Invc.py`
- `bot/cogs/commands/Media.py`
- `bot/cogs/commands/afk.py`
- `bot/cogs/commands/ai.py`
- `bot/cogs/commands/anti_unwl.py`
- `bot/cogs/commands/anti_wl.py`
- `bot/cogs/commands/antinuke.py`
- `bot/cogs/commands/automod.py`
- `bot/cogs/commands/autoreact.py`
- `bot/cogs/commands/autoresponder.py`
- `bot/cogs/commands/autorole.py`
- `bot/cogs/commands/blackjack.py`
- `bot/cogs/commands/blacklist.py`
- `bot/cogs/commands/block.py`
- `bot/cogs/commands/booster.py`
- `bot/cogs/commands/calc.py`
- `bot/cogs/commands/counting.py`
- `bot/cogs/commands/customrole.py`
- `bot/cogs/commands/dms.py`
- `bot/cogs/commands/emergency.py`
- `bot/cogs/commands/encryption.py`
- `bot/cogs/commands/extra.py`
- `bot/cogs/commands/extraown.py`
- `bot/cogs/commands/fastgreet.py`
- `bot/cogs/commands/filters.py`
- `bot/cogs/commands/fun.py`
- `bot/cogs/commands/general.py`
- `bot/cogs/commands/giveaway.py`
- `bot/cogs/commands/help.py`
- `bot/cogs/commands/help_backup.txt`
- `bot/cogs/commands/ignore.py`
- `bot/cogs/commands/image.py`
- `bot/cogs/commands/imagine.py`
- `bot/cogs/commands/j2c.py`
- `bot/cogs/commands/jail.py`
- `bot/cogs/commands/joindm.py`
- `bot/cogs/commands/leveling.py`
- `bot/cogs/commands/leveling_original.py`
- `bot/cogs/commands/logging.py`
- `bot/cogs/commands/map.py`
- `bot/cogs/commands/messages.py`
- `bot/cogs/commands/minecraft.py`
- `bot/cogs/commands/msgpack.py`
- `bot/cogs/commands/music.py`
- `bot/cogs/commands/nightmode.py`
- `bot/cogs/commands/nitro.py`
- `bot/cogs/commands/notify.py`
- `bot/cogs/commands/np.py`
- `bot/cogs/commands/owner.py`
- `bot/cogs/commands/owner2.py`
- `bot/cogs/commands/qr.py`
- `bot/cogs/commands/reactionroles.py`
- `bot/cogs/commands/slots.py`
- `bot/cogs/commands/stats.py`
- `bot/cogs/commands/status.py`
- `bot/cogs/commands/steal.py`
- `bot/cogs/commands/stickymessage.py`
- `bot/cogs/commands/ticket.py`
- `bot/cogs/commands/timer.py`
- `bot/cogs/commands/tracking.py`
- `bot/cogs/commands/translate.py`
- `bot/cogs/commands/vanityroles.py`
- `bot/cogs/commands/verification.py`
- `bot/cogs/commands/voice.py`
- `bot/cogs/commands/welcome.py`
- `bot/cogs/commands/youtube.py`

## 📁 Antinuke System (Cogs)

- `bot/cogs/antinuke/antiIntegration.py`
- `bot/cogs/antinuke/anti_member_update.py`
- `bot/cogs/antinuke/antiban.py`
- `bot/cogs/antinuke/antibotadd.py`
- `bot/cogs/antinuke/antichcr.py`
- `bot/cogs/antinuke/antichdl.py`
- `bot/cogs/antinuke/antichup.py`
- `bot/cogs/antinuke/antieveryone.py`
- `bot/cogs/antinuke/antiguild.py`
- `bot/cogs/antinuke/antikick.py`
- `bot/cogs/antinuke/antiprune.py`
- `bot/cogs/antinuke/antirlcr.py`
- `bot/cogs/antinuke/antirldl.py`
- `bot/cogs/antinuke/antirlup.py`
- `bot/cogs/antinuke/antiwebhook.py`
- `bot/cogs/antinuke/antiwebhookcr.py`
- `bot/cogs/antinuke/antiwebhookdl.py`
- `bot/cogs/antinuke/extra events (unused)/antiemocr.py`
- `bot/cogs/antinuke/extra events (unused)/antiemodl.py`
- `bot/cogs/antinuke/extra events (unused)/antiemoup.py`
- `bot/cogs/antinuke/extra events (unused)/antisticker.py`
- `bot/cogs/antinuke/extra events (unused)/antiunban.py`

## 📁 Automod System (Cogs)

- `bot/cogs/automod/anti_emoji_spam.py`
- `bot/cogs/automod/anti_invites.py`
- `bot/cogs/automod/anti_mass_mention.py`
- `bot/cogs/automod/anticaps.py`
- `bot/cogs/automod/antilink.py`
- `bot/cogs/automod/antispam.py`

## 📁 Moderation System (Cogs)

- `bot/cogs/moderation/ban.py`
- `bot/cogs/moderation/ban.txt`
- `bot/cogs/moderation/hide.py`
- `bot/cogs/moderation/hide.txt`
- `bot/cogs/moderation/kick.py`
- `bot/cogs/moderation/kick.txt`
- `bot/cogs/moderation/lock.py`
- `bot/cogs/moderation/message.py`
- `bot/cogs/moderation/moderation.py`
- `bot/cogs/moderation/role.py`
- `bot/cogs/moderation/snipe.py`
- `bot/cogs/moderation/snipe.txt`
- `bot/cogs/moderation/timeout.py`
- `bot/cogs/moderation/topcheck.py`
- `bot/cogs/moderation/unban.py`
- `bot/cogs/moderation/unhide.py`
- `bot/cogs/moderation/unhide.txt`
- `bot/cogs/moderation/unlock.py`
- `bot/cogs/moderation/unmute.py`
- `bot/cogs/moderation/warn.py`

## 📁 Event Listeners (Cogs)

- `bot/cogs/events/Errors.py`
- `bot/cogs/events/ai.py`
- `bot/cogs/events/auto.py`
- `bot/cogs/events/autoblacklist.py`
- `bot/cogs/events/autoreact.py`
- `bot/cogs/events/autorole.py`
- `bot/cogs/events/greet2.py`
- `bot/cogs/events/mention.py`
- `bot/cogs/events/mentionold.txt`
- `bot/cogs/events/on_guild.py`
- `bot/cogs/events/react.py`
- `bot/cogs/events/stickymessage.py`

## 📁 Zyrox Help & Subsystems

- `bot/cogs/zyrox/ai.py`
- `bot/cogs/zyrox/antinuke.py`
- `bot/cogs/zyrox/automod.py`
- `bot/cogs/zyrox/birth.py`
- `bot/cogs/zyrox/booster.py`
- `bot/cogs/zyrox/counting.py`
- `bot/cogs/zyrox/encryption.py`
- `bot/cogs/zyrox/extra.py`
- `bot/cogs/zyrox/fun.py`
- `bot/cogs/zyrox/games.py`
- `bot/cogs/zyrox/general.py`
- `bot/cogs/zyrox/giveaway.py`
- `bot/cogs/zyrox/ignore.py`
- `bot/cogs/zyrox/inviteTracker.py`
- `bot/cogs/zyrox/j2c.py`
- `bot/cogs/zyrox/joindm.py`
- `bot/cogs/zyrox/leveling.py`
- `bot/cogs/zyrox/logging.py`
- `bot/cogs/zyrox/mc.py`
- `bot/cogs/zyrox/moderation.py`
- `bot/cogs/zyrox/music.py`
- `bot/cogs/zyrox/server.py`
- `bot/cogs/zyrox/sticky.py`
- `bot/cogs/zyrox/ticket.py`
- `bot/cogs/zyrox/vanity.py`
- `bot/cogs/zyrox/verify.py`
- `bot/cogs/zyrox/voice.py`
- `bot/cogs/zyrox/welcome.py`

## 📁 Standalone Minigames

- `bot/games/__init__.py`
- `bot/games/battleship.py`
- `bot/games/chess_game.py`
- `bot/games/connect_four.py`
- `bot/games/country_guess.py`
- `bot/games/reaction_test.py`
- `bot/games/rps.py`
- `bot/games/tictactoe.py`
- `bot/games/twenty_48.py`
- `bot/games/typeracer.py`
- `bot/games/utils.py`
- `bot/games/wordle.py`
- `bot/games/assets/words.txt`
- `bot/games/button_games/__init__.py`
- `bot/games/button_games/battleship_buttons.py`
- `bot/games/button_games/chess_buttons.py`
- `bot/games/button_games/connect_four_buttons.py`
- `bot/games/button_games/country_guess_buttons.py`
- `bot/games/button_games/lights_out.py`
- `bot/games/button_games/memory_game.py`
- `bot/games/button_games/number_slider.py`
- `bot/games/button_games/reaction_test_buttons.py`
- `bot/games/button_games/rps_buttons.py`
- `bot/games/button_games/tictactoe_buttons.py`
- `bot/games/button_games/twenty_48_buttons.py`
- `bot/games/button_games/wordle_buttons.py`

## 📁 Bot Shared Utilities & Database Drivers

- `bot/utils/Tools.py`
- `bot/utils/__init__.py`
- `bot/utils/ai_utils.py`
- `bot/utils/config.py`
- `bot/utils/config_loader.py`
- `bot/utils/cv2.py`
- `bot/utils/emoji.py`
- `bot/utils/help.py`
- `bot/utils/paginator.py`
- `bot/utils/paginators.py`
- `bot/utils/sync_emojis.py`
- `bot/utils/tunnel.py`

## 📁 Database Files & JSON Storage

- `bot/db/_db.py`
- `bot/db/admin_config.db`
- `bot/db/afk.db`
- `bot/db/ai_data.db`
- `bot/db/anti.db`
- `bot/db/automod.db`
- `bot/db/autoreact.db`
- `bot/db/autoresponder.db`
- `bot/db/autorole.db`
- `bot/db/badges.db`
- `bot/db/block.db`
- `bot/db/blword.db`
- `bot/db/boost.db`
- `bot/db/counting.json`
- `bot/db/customrole.db`
- `bot/db/emergency.db`
- `bot/db/fastgreet.db`
- `bot/db/giveaways.db`
- `bot/db/ignore.db`
- `bot/db/invc.db`
- `bot/db/invite.db`
- `bot/db/jail.db`
- `bot/db/leveling.db`
- `bot/db/media.db`
- `bot/db/messages.db`
- `bot/db/minecraft.db`
- `bot/db/notify.db`
- `bot/db/np.db`
- `bot/db/prefix.db`
- `bot/db/stats.db`
- `bot/db/stickymessages.db`
- `bot/db/ticket.db`
- `bot/db/ticket.db-journal`
- `bot/db/topcheck.db`
- `bot/db/vanity.db`
- `bot/db/verification.db`
- `bot/db/warn.db`
- `bot/db/welcome.db`
- `bot/jsondb/birthdays.json`
- `bot/jsondb/logging_config.json`

## 📁 Next.js 14 Web Dashboard Pages & Routes

- `dashboard/app/globals.css`
- `dashboard/app/layout.tsx`
- `dashboard/app/page.tsx`
- `dashboard/app/terms/page.tsx`
- `dashboard/app/dashboard/error.tsx`
- `dashboard/app/dashboard/layout.tsx`
- `dashboard/app/dashboard/loading.tsx`
- `dashboard/app/dashboard/page.tsx`
- `dashboard/app/dashboard/guild/[guildId]/layout.tsx`
- `dashboard/app/dashboard/guild/[guildId]/loading.tsx`
- `dashboard/app/dashboard/guild/[guildId]/page.tsx`
- `dashboard/app/dashboard/guild/[guildId]/verification/page.tsx`
- `dashboard/app/dashboard/guild/[guildId]/invites/page.tsx`
- `dashboard/app/dashboard/guild/[guildId]/invcrole/page.tsx`
- `dashboard/app/dashboard/guild/[guildId]/tickets/page.tsx`
- `dashboard/app/dashboard/guild/[guildId]/settings/page.tsx`
- `dashboard/app/dashboard/guild/[guildId]/j2c/page.tsx`
- `dashboard/app/dashboard/guild/[guildId]/welcome/page.tsx`
- `dashboard/app/dashboard/guild/[guildId]/automod/page.tsx`
- `dashboard/app/dashboard/guild/[guildId]/autoreact/page.tsx`
- `dashboard/app/dashboard/guild/[guildId]/antinuke/page.tsx`
- `dashboard/app/dashboard/guild/[guildId]/logging/page.tsx`
- `dashboard/app/dashboard/guild/[guildId]/vanityroles/page.tsx`
- `dashboard/app/dashboard/guild/[guildId]/customroles/page.tsx`
- `dashboard/app/dashboard/guild/[guildId]/leveling/page.tsx`
- `dashboard/app/dashboard/guild/[guildId]/leveling/leaderboard/page.tsx`
- `dashboard/app/dashboard/guild/[guildId]/autorole/page.tsx`
- `dashboard/app/dashboard/guild/[guildId]/joindm/page.tsx`
- `dashboard/app/dashboard/guild/[guildId]/reactionroles/page.tsx`
- `dashboard/app/dashboard/guild/[guildId]/tracking/page.tsx`
- `dashboard/app/dashboard/admin/page.tsx`
- `dashboard/app/dashboard/guilds/page.tsx`
- `dashboard/app/privacy/page.tsx`
- `dashboard/app/docs/page.tsx`
- `dashboard/app/api/auth/[...nextauth]/route.ts`

## 📁 Dashboard UI Components

- `dashboard/components/auth-provider.tsx`
- `dashboard/components/guild-tabs.tsx`
- `dashboard/components/dashboard/admin-content.tsx`
- `dashboard/components/dashboard/antinuke-form.tsx`
- `dashboard/components/dashboard/automod-form.tsx`
- `dashboard/components/dashboard/autorole-form.tsx`
- `dashboard/components/dashboard/customroles-form.tsx`
- `dashboard/components/dashboard/form-elements.tsx`
- `dashboard/components/dashboard/j2c-form.tsx`
- `dashboard/components/dashboard/leveling-form.tsx`
- `dashboard/components/dashboard/logging-form.tsx`
- `dashboard/components/dashboard/metric-card.tsx`
- `dashboard/components/dashboard/page-header.tsx`
- `dashboard/components/dashboard/reactionroles-form.tsx`
- `dashboard/components/dashboard/server-card.tsx`
- `dashboard/components/dashboard/settings-form.tsx`
- `dashboard/components/dashboard/tickets-form.tsx`
- `dashboard/components/dashboard/vanityrole-form.tsx`
- `dashboard/components/dashboard/verification-form.tsx`
- `dashboard/components/dashboard/welcome-form.tsx`
- `dashboard/components/ui/button.tsx`
- `dashboard/components/ui/card.tsx`
- `dashboard/components/ui/input.tsx`
- `dashboard/components/ui/label.tsx`
- `dashboard/components/ui/select.tsx`
- `dashboard/components/ui/sonner.tsx`
- `dashboard/components/ui/switch.tsx`
- `dashboard/components/ui/table.tsx`
- `dashboard/components/ui/textarea.tsx`

## 📁 Dashboard Library & Hooks

- `dashboard/lib/api.ts`
- `dashboard/lib/auth.ts`
- `dashboard/lib/utils.ts`
- `dashboard/hooks/use-auth.ts`
- `dashboard/types/api.ts`
- `dashboard/types/index.ts`
- `dashboard/types/next-auth.d.ts`

## 📁 Dashboard Configuration & Root

- `dashboard/package.json`
- `dashboard/tailwind.config.ts`
- `dashboard/next.config.mjs`
- `dashboard/tsconfig.json`

