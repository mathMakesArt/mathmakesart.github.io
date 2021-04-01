---
layout: post
title:  "Monthly Report (March 2021)"
author: "MathMakesArt"
date:   2020-04-01 06:00 -0000
tags: report
categories:
  - blog

# Variables for table generation
report_tezos_price_usd: 4.82
report_number_collected: 446
report_total_collection_costs: 31.226882
report_max_collection_cost: 5.0
report_average_collection_cost: 0.07113185
report_number_collection_listed: 0
report_total_collection_listing_costs: 0.0
report_number_collection_sold: 0
report_total_collection_sale_revenue: 0.0
report_average_collection_sale_revenue: 0.0
report_total_collection_expenses: 31.226882
report_total_collection_revenue: 0.0
report_total_collection_profit: -31.226882
report_number_minted: 13
report_number_minted_single: 9
report_number_minted_multiple: 4
report_number_minted_total_editions: 431
report_total_mint_costs: 0.127216
report_number_swaps: 21
report_number_swap_editions: 288
report_total_swap_costs: 0.208018
report_number_primary_sales: 37
report_total_primary_sale_revenue: 16.6075
report_average_primary_sale_revenue: 0.448851351
report_max_primary_sale_revenue: 4.48
report_number_royalties: 40
report_number_secondary_sales: 3
report_total_royalty_revenue: 2.723
report_average_royalty_revenue: 0.068075
report_max_royalty_revenue: 0.512
report_summary_artist_expenses: 0.335234
report_summary_artist_revenue: 19.3305
report_summary_artist_profit: 18.995266
report_summary_final_profit: -12.231616
---
<style type="text/css" media="screen">
    /* CSS taken from generator at divtable.com */
    .divTable{
        display: table;
        width: 100%;
    }
    .divTableRow {
        display: table-row;
    }
    .divTableHeading {
        background-color: #EEE;
        display: table-header-group;
    }
    .divTableCell, .divTableHead {
        border: 1px solid #999999;
        display: table-cell;
        padding: 3px 10px;
    }
    .divTableHeading {
        background-color: #EEE;
        display: table-header-group;
        font-weight: bold;
    }
    .divTableFoot {
        background-color: #EEE;
        display: table-footer-group;
        font-weight: bold;
    }
    .divTableBody {
        display: table-row-group;
    }
</style>
<br />
<h3><strong>Introduction:</strong></h3>
In running the MathMakesArt website and associated accounts, I hope to be as transparent as possible. As part of this, on a monthly basis, I plan to release reports detailing my NFT sales and other transactions.
<br />
<br />
<h3><strong>Twitter:</strong></h3>
Twitter seems to be a pretty central part of the NFT world, so I think it's worth mentioning. I started using Twitter as <strong><a href="https://twitter.com/mathmakesart">@mathMakesArt</a></strong> on 2021 March 03. In this first month, I've gone from <strong>0</strong> followers to <strong>258</strong> followers! I am very grateful to everyone who has followed me on social media (more links in the footer if you're curious).
<br />
As a bonus, I gave 25 editions of my <strong><a href="https://www.hicetnunc.xyz/objkt/9953">25 Hashes</a></strong> NFT to Twitter users who submitted addresses and transaction hashes as input strings for art creation. Additionally, 222 free copies of my <strong><a href="https://www.hicetnunc.xyz/objkt/12835">"#OBJKT4OBJKT" Visualized</a></strong> NFT were distributed as a part of the OBJKT4OBJKT swap weekend on HicEtNunc, and the remaining copies have been reserved for my first 110 Twitter followers.
<br />
<br />
<h3><strong>Notable Exceptions:</strong></h3>
This month, I won a 1.0 ETH prize from Twitter user and artist @compusophy. I subsequently converted this ETH to 420 XTZ. I will be using this 420 XTZ sum to help fund the activities of other artists on the Tezos blockchain, focusing on the HicEtNunc platform and especially targeting people who are new to crypto art.
<br />
For the purposes of this report (and subsequent reports) I will not include the 420 XTZ sum in my explanation of revenue.
<br />
<br />
<h3><strong>Pricing Clarification:</strong></h3>
At the time of writing on 2021 April 01, 1 Tezos has a price of <strong>${{ page.report_tezos_price_usd }}</strong> and this value is used in some of the calculations below.
<br />
Eventually I might update the website to pull from a live price feed, but currently <strong>${{ page.report_tezos_price_usd }}</strong> is the value used.
<br />
<br />
<h3><strong>Collection Details:</strong></h3>
<div class="divTable">
<div class="divTableBody">
<div class="divTableRow">
<div class="divTableCell"><strong>Property</strong></div>
<div class="divTableCell"><strong>Value</strong></div>
<div class="divTableCell"><strong>USD</strong></div>
</div>
<div class="divTableRow">
<div class="divTableCell">Number of NFTs collected</div>
<div class="divTableCell">{{- page.report_number_collected -}}</div>
<div class="divTableCell">N/A</div>
</div>
<div class="divTableRow">
<div class="divTableCell">Total NFT collection costs</div>
<div class="divTableCell">{{- page.report_total_collection_costs -}}</div>
<div class="divTableCell">$ {{- page.report_tezos_price_usd | times:page.report_total_collection_costs | round: 2 -}}</div>
</div>
<div class="divTableRow">
<div class="divTableCell">Max NFT collection cost</div>
<div class="divTableCell">{{- page.report_max_collection_cost -}}</div>
<div class="divTableCell">$ {{- page.report_tezos_price_usd | times:page.report_max_collection_cost | round: 2 -}}</div>
</div>
<div class="divTableRow">
<div class="divTableCell">Average NFT collection cost</div>
<div class="divTableCell">{{- page.report_average_collection_cost -}}</div>
<div class="divTableCell">$ {{- page.report_tezos_price_usd | times:page.report_average_collection_cost | round: 2 -}}</div>
</div>
<div class="divTableRow">
<div class="divTableCell">Number of collection NFTs listed</div>
<div class="divTableCell">{{- page.report_number_collection_listed -}}</div>
<div class="divTableCell">N/A</div>
</div>
<div class="divTableRow">
<div class="divTableCell">Total collection listing costs</div>
<div class="divTableCell">{{- page.report_total_collection_listing_costs -}}</div>
<div class="divTableCell">$ {{- page.report_tezos_price_usd | times:page.report_total_collection_listing_costs | round: 2 -}}</div>
</div>
<div class="divTableRow">
<div class="divTableCell">Number of collection NFTs sold</div>
<div class="divTableCell">{{- page.report_number_collection_sold -}}</div>
<div class="divTableCell">N/A</div>
</div>
<div class="divTableRow">
<div class="divTableCell">Total collection NFT sale revenue</div>
<div class="divTableCell">{{- page.report_total_collection_sale_revenue -}}</div>
<div class="divTableCell">$ {{- page.report_tezos_price_usd | times:page.report_total_collection_sale_revenue | round: 2 -}}</div>
</div>
<div class="divTableRow">
<div class="divTableCell">Average collection NFT sale revenue</div>
<div class="divTableCell">{{- page.report_average_collection_sale_revenue -}}</div>
<div class="divTableCell">$ {{- page.report_tezos_price_usd | times:page.report_average_collection_sale_revenue | round: 2 -}}</div>
</div>
<div class="divTableRow">
<div class="divTableCell">Total collection expenses</div>
<div class="divTableCell">{{- page.report_total_collection_expenses -}}</div>
<div class="divTableCell">$ {{- page.report_tezos_price_usd | times:page.report_total_collection_expenses | round: 2 -}}</div>
</div>
<div class="divTableRow">
<div class="divTableCell">Total collection revenue</div>
<div class="divTableCell">{{- page.report_total_collection_revenue -}}</div>
<div class="divTableCell">$ {{- page.report_tezos_price_usd | times:page.report_total_collection_revenue | round: 2 -}}</div>
</div>
<div class="divTableRow">
<div class="divTableCell">Total collection profit</div>
<div class="divTableCell">{{- page.report_total_collection_profit -}}</div>
<div class="divTableCell">$ {{- page.report_tezos_price_usd | times:page.report_total_collection_profit | round: 2 -}}</div>
</div>
</div>
</div>
<br />
<br />
<h3><strong>Art Sale Details:</strong></h3>
<div class="divTable">
<div class="divTableBody">
<div class="divTableRow">
<div class="divTableCell"><strong>Property</strong></div>
<div class="divTableCell"><strong>Value</strong></div>
<div class="divTableCell"><strong>USD</strong></div>
</div>
<div class="divTableRow">
<div class="divTableCell">Number of NFTs minted</div>
<div class="divTableCell">{{- page.report_number_minted -}}</div>
<div class="divTableCell">N/A</div>
</div>
<div class="divTableRow">
<div class="divTableCell">Number of single-edition mints</div>
<div class="divTableCell">{{- page.report_number_minted_single -}}</div>
<div class="divTableCell">N/A</div>
</div>
<div class="divTableRow">
<div class="divTableCell">Number of multi-edition mints</div>
<div class="divTableCell">{{- page.report_number_minted_multiple -}}</div>
<div class="divTableCell">N/A</div>
</div>
<div class="divTableRow">
<div class="divTableCell">Total number of editions minted</div>
<div class="divTableCell">{{- page.report_number_minted_total_editions -}}</div>
<div class="divTableCell">N/A</div>
</div>
<div class="divTableRow">
<div class="divTableCell">Total mint costs</div>
<div class="divTableCell">{{- page.report_total_mint_costs -}}</div>
<div class="divTableCell">$ {{- page.report_tezos_price_usd | times:page.report_total_mint_costs | round: 2 -}}</div>
</div>
<div class="divTableRow">
<div class="divTableCell">Number of swaps created</div>
<div class="divTableCell">{{- page.report_number_swaps -}}</div>
<div class="divTableCell">N/A</div>
</div>
<div class="divTableRow">
<div class="divTableCell">Total number of editions in swaps</div>
<div class="divTableCell">{{- page.report_number_swap_editions -}}</div>
<div class="divTableCell">N/A</div>
</div>
<div class="divTableRow">
<div class="divTableCell">Total swap creation costs</div>
<div class="divTableCell">{{- page.report_total_swap_costs -}}</div>
<div class="divTableCell">$ {{- page.report_tezos_price_usd | times:page.report_total_swap_costs | round: 2 -}}</div>
</div>
<div class="divTableRow">
<div class="divTableCell">Number of primary sales</div>
<div class="divTableCell">{{- page.report_number_primary_sales -}}</div>
<div class="divTableCell">N/A</div>
</div>
<div class="divTableRow">
<div class="divTableCell">Total received from primary sales</div>
<div class="divTableCell">{{- page.report_total_primary_sale_revenue -}}</div>
<div class="divTableCell">$ {{- page.report_tezos_price_usd | times:page.report_total_primary_sale_revenue | round: 2 -}}</div>
</div>
<div class="divTableRow">
<div class="divTableCell">Average received per primary sale</div>
<div class="divTableCell">{{- page.report_average_primary_sale_revenue -}}</div>
<div class="divTableCell">$ {{- page.report_tezos_price_usd | times:page.report_average_primary_sale_revenue | round: 2 -}}</div>
</div>
<div class="divTableRow">
<div class="divTableCell">Max received from a primary sale</div>
<div class="divTableCell">{{- page.report_max_primary_sale_revenue -}}</div>
<div class="divTableCell">$ {{- page.report_tezos_price_usd | times:page.report_max_primary_sale_revenue | round: 2 -}}</div>
</div>
<div class="divTableRow">
<div class="divTableCell">Number of royalties received</div>
<div class="divTableCell">{{- page.report_number_royalties -}}</div>
<div class="divTableCell">N/A</div>
</div>
<div class="divTableRow">
<div class="divTableCell">Number of secondary sales</div>
<div class="divTableCell">{{- page.report_number_secondary_sales -}}</div>
<div class="divTableCell">N/A</div>
</div>
<div class="divTableRow">
<div class="divTableCell">Total received from royalties</div>
<div class="divTableCell">{{- page.report_total_royalty_revenue -}}</div>
<div class="divTableCell">$ {{- page.report_tezos_price_usd | times:page.report_total_royalty_revenue | round: 2 -}}</div>
</div>
<div class="divTableRow">
<div class="divTableCell">Average received per royalty</div>
<div class="divTableCell">{{- page.report_average_royalty_revenue -}}</div>
<div class="divTableCell">$ {{- page.report_tezos_price_usd | times:page.report_average_royalty_revenue | round: 2 -}}</div>
</div>
<div class="divTableRow">
<div class="divTableCell">Max received from a royalty</div>
<div class="divTableCell">{{- page.report_max_royalty_revenue -}}</div>
<div class="divTableCell">$ {{- page.report_tezos_price_usd | times:page.report_max_royalty_revenue | round: 2 -}}</div>
</div>
</div>
</div>
<br />
<br />
<h3><strong>Conclusion:</strong></h3>
<div class="divTable">
<div class="divTableBody">
<div class="divTableRow">
<div class="divTableCell"><strong>Property</strong></div>
<div class="divTableCell"><strong>Value</strong></div>
<div class="divTableCell"><strong>USD</strong></div>
</div>
<div class="divTableRow">
<div class="divTableCell">Total artist expenses</div>
<div class="divTableCell">{{- page.report_summary_artist_expenses -}}</div>
<div class="divTableCell">$ {{- page.report_tezos_price_usd | times:page.report_summary_artist_expenses | round: 2 -}}</div>
</div>
<div class="divTableRow">
<div class="divTableCell">Total artist revenue</div>
<div class="divTableCell">{{- page.report_summary_artist_revenue -}}</div>
<div class="divTableCell">$ {{- page.report_tezos_price_usd | times:page.report_summary_artist_revenue | round: 2 -}}</div>
</div>
<div class="divTableRow">
<div class="divTableCell">Total artist profit</div>
<div class="divTableCell">{{- page.report_summary_artist_profit -}}</div>
<div class="divTableCell">$ {{- page.report_tezos_price_usd | times:page.report_summary_artist_profit | round: 2 -}}</div>
</div>
<div class="divTableRow">
<div class="divTableCell">Final profit</div>
<div class="divTableCell">{{- page.report_summary_final_profit -}}</div>
<div class="divTableCell">$ {{- page.report_tezos_price_usd | times:page.report_summary_final_profit | round: 2 -}}</div>
</div>
</div>
</div>
