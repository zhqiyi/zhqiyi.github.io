---
title: OpenKnow 架构笔记
date: 2026-06-21
tags: [OpenKnow, RAG, 图谱, 架构]
---

## 基本信息

- GitLab: http://192.168.31.188:53080/llm-ai-group/openknow_recon
- 本地克隆: /opt/data/openknow_recon/
- SSH 端口: 2222
- 访问 Token: 存于 .netrc 和 .git-credentials

## 架构

前后端分离：
- 前端: React + Vite + TypeScript
- 后端: FastAPI + SQLModel + Pydantic
- 存储: PostgreSQL + LanceDB（向量）

## 已实现功能（Phase 4）

- RAG（文档分块 + 向量检索）
- GraphRAG（知识图谱多跳推理）
- RBAC 权限系统（OWNER/ADMIN/EDITOR/VIEWER/GUEST）
- 文档生命周期管理（draft → review → published）
- SSO / OIDC / LDAP 企业登录
- Chat API（对话 CRUD + 流式响应）

## 接口示例

- Chat: `/api/workspaces/{wsId}/chat/`
- GraphRAG: `/api/workspaces/{wsId}/graphrag/query`
- 文档: `/api/workspaces/{wsId}/documents/`
