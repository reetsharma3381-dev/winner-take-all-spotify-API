# Spotify Superstar Economics

This is to test whether artist popularity/streams follow a power-law (Pareto) distribution
consistent with "winner-take-all" dynamics, and whether concentration has
increased over time. A panel regression testing candidate drivers
(Discover Weekly era algorithmic curation, TikTok era virality).

Analysis has been done for a span of almost a decade (2016-2025)

The Spotify Web API does not expose historical raw stream counts. It gives a popularity score (0–100) and follower counts, both as *currentsnapshots only*, you can't ask "what was this artist's popularity in 2018."
