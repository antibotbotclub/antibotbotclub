---
title: "[WIP] Whitepaper"
layout: "single"
description: "Turning drains into gains with the Anti Bot Bot Club."
summary: "Turning drains into gains with the Anti Bot Bot Club."
# tags: ["whitepaper", "bots", "solana", "blockchain", "cybersecurity"]
ShowReadingTime: false
ShowWordCount: false
hideAuthor: true
---

# Abstract

__*NOTE: The whitepaper is work-in-progress and will be updated.*__

Anti Bot Bot Club is an organisation that aims to battle the huge amount of bots on the Solana blockchain. We aim to turn drains from bots into gains. Over time we will develop and improve our anti-bots to continously help the community. A part of the $ABBC coin will be put into a fund to get security researchers, auditors and developers onboard. Our goal with the fund is to stimulate the strong web3 community into the battle against the bots. 

## Problem

In the rapidly evolving landscape of cryptocurrency, the rise of bots has not gone unnoticed. 



## Solution

We build anti-bots.

By deploying anti-bots we aim to battle these bots on their own domain. Besides the creation of anti-bots we will fund security research through the tokenomics of $ABBC.

<!-- ```rust {linenos=true,hl_lines=[14,20,27]}
pub mod ins;
pub mod state;

use anchor_lang::prelude::*;
use instructions::*;
//replace the program id that you get after deploying the program
declare_id!("GxKdeadbeefdeadbeefdeadbeef");

#[program]
pub mod my_sol_data {
    use super::*;
    pub fn init_data(ctx: Context<InitMyData>) -> ProgramResult {
        
        let acc = &mut ctx.accounts.data;
        acc.number = 0; 
        acc.message = String::from("MyData initialized!");

        // we store the public key of the signer to the owner field
        // of MyData
        acc.owner = ctx.accounts.owner.key();
                           
        Ok(())
    }
  
    pub fn update_data (ctx : Context<UpdateMyData>, number : u8, message : String) -> ProgramResult {

        let acc = &mut ctx.accounts.data;
        acc.number = number;
        acc.message = message;
  
        Ok(())
    }
}
``` -->

## Tokenomics

The complete tokenomics will be shared shortly. As mentioned above, a part of the $ABBC pool will be used as funding for research. Read more on the [Tokenomics](/tokenomics) page. 

## Investors

Please contact [investors[@]antibotbot.club](mailt:investors@antibotbot.club) if you are an investor.
