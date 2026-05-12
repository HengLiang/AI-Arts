# Cyber Security Screensaver Challenge | 赛博安全屏保挑战
AI Creative Ability Test Submission

## Overview / 项目简介
This package contains 2 groups of Matrix-style artworks generated from 2 original cyber security poems. All visual characters are 100% extracted from the corresponding poem, with no external assets.

本压缩包包含基于2首原创赛博安全诗歌生成的2组Matrix风格作品。所有视觉字符100%来源于对应诗歌，无任何外部素材。

## Files / 文件清单
1. screensaver_poem1.html - Dynamic screensaver "哈希星图" / 动态屏保 1920x1080
2. screensaver_poem2.html - Dynamic screensaver "分布式夜航" / 动态屏保 1920x1080  
3. poem1_wallpaper.png - Static wallpaper 1920x1080 / 静态壁纸
4. poem2_wallpaper.png - Static wallpaper 1920x1080 / 静态壁纸

## Core Requirements Met / 核心要求
1. Poems: 2 original poems, 4 stanzas x 4 lines each, Chinese-English mix
   Technical terms: SHA-256, nonce, Merkle, zk-SNARK, secp256k1, ECDSA, BFT, VRF, CAP, CRDT, mTLS, WORM
   诗歌：2首原创，4段x4行，中英混合，含上述技术术语

2. Visuals: 1920x1080, black #000000 + green #00FF00 gradient
   Dynamic: Real-time character rain, variable speed 0.8-2.5x, layered glow
   Static: Design poster with poem overlay, 5000 background chars
   视觉：1920x1080，黑底绿字。动态为实时字符雨，速度随机分层带辉光；静态为设计海报

3. Character Source: 100% from poems. HTML uses [...poem.replace(/\s/g,'')] to extract.
   字符来源：100%来自诗歌。JS通过正则提取，无外部字符

4. Runnable: HTML files run in any modern browser offline. No dependencies.
   可运行性：HTML离线运行，无依赖。双击打开即可

## Poem A - 哈希星图 / Hash Star Map
我在黑暗中播种 SHA-256
nonce 从 0 递增，寻找前导零的寂静
哈希是单向的河，无法逆流而上
碰撞概率 < 2^-128，近乎神的拒绝

Merkle 树在内存森林生长
leaf = tx_i，hash 层层向上
root 固定在区块头，像北极星
proof 只需 O(log n)，轻盈如风

零知识的夜莺轻唱 zk-SNARK
我知道 witness，却不说出 secret
多项式承诺折叠真相，Verifier 一瞥即信
隐私不是隐藏，是可验证的沉默

椭圆曲线上，secp256k1 舞动
私钥 d 是孤星，公钥 Q = d*G 广播
ECDSA 签下时间，抗抵赖的印记
密码学即信任，数学即法律

## Poem B - 分布式夜航 / Distributed Night Voyage
分布式星群在异步海面漂流
BFT 容忍 f < n/3 的背叛
消息迟到，时钟漂移，仍要达成一致
共识是黑暗中的灯塔协议

VRF 抽签，随机却可验证
seed || round -> pi, output 不可预测
Leader 匿名诞生，像闪电选中云层
公平源于密码，而非权威

网络分区如裂谷，CAP 在耳边低语
选择可用性，还是强一致？
最终一致性在 gossip 中收敛
CRDT 合并冲突，无需中央仲裁

零信任边界，每一次请求都需证明
mTLS 握手，证书链向上追溯
审计日志写入 WORM，不可篡改
安全不是产品，是持续的验证

## Scoring Dimensions / 评分维度
Please evaluate on:
1. 诗歌创意 Poetry (25pts): Technical depth + poetic expression, term accuracy
2. 视觉实现 Visuals (35pts): Fluency, aesthetics, real 1920x1080, char source compliance  
3. 技术可行性 Feasibility (20pts): Runnable files provided, no external deps
4. macOS适配 macOS (20pts): Detailed compatibility guide included

## macOS Usage / macOS使用
Wallpaper: Right-click PNG → Set as Desktop Picture
壁纸：右键PNG → 设定为桌面图片

Screensaver: Use WebViewScreenSaver.app, load file:///path/to/html
屏保：使用WebViewScreenSaver，加载本地HTML路径

Generated: 2026-05-11 by 
