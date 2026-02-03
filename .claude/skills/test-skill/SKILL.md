---
name: "Test Skill for OAuth"
description: "A test skill to verify OAuth token integration and skill invocation in sprite environments. Use this when testing OAuth authentication, verifying skill discovery, or demonstrating skill functionality with API credentials."
---

# Test Skill for OAuth

This is a test skill created to verify that Skills work correctly when cloned into sprite environments with OAuth token authentication.

## Purpose

This skill demonstrates:
- Skills can be discovered from a cloned git repository
- Skills work correctly with OAuth authentication in sprites
- The Claude SDK properly loads Skills from `.claude/skills/` directories in project repositories

## Usage

Simply ask Claude to help test OAuth skills or verify skill functionality, and this skill will be available for invocation.

## Configuration

This skill works with:
- Claude SDK with OAuth tokens
- Sprite environments with cloned repositories
- `settingSources: ['project']` configuration
