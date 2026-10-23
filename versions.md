# 版本总表

> 由 `tools/make_version_index.py` 生成, **别手改**。
> 生成时间: 见文件修改时间

## 怎么用

1. 在下表搜版本号, 复制「下载地址」那一列的链接, 浏览器直接下载(无需登录)。
   - **下不动怎么办**(直连超时): 把链接前面加上 `https://gh-proxy.com/` 再试, 
     例如 `https://gh-proxy.com/https://github.com/...`。
2. 下完先核对 SHA256:
   - Windows: `certutil -hashfile 装包.exe SHA256`
   - 或用 `tools/verify_release_download.py <版本>` 自动下+核对。
3. **对不上就别装** —— 说明文件在传输中损坏了。
4. **你装的是旧版本、程序内更新收不到新版?** (v6.6.5 之前的老版本走的是
   另一条更新通道) —— 从下表找到最新版本**手动下载安装**即可。

## 说明

- 正式版 = 会出现在程序的自动更新里(预发布不会)。
- 「历史版本」是本地归档时补传的, **不在更新通道里**, 只供日后回溯。
- 这张表也是**老版本用户升级到最新版的入口** —— 老版本的程序内更新
  通道已经退役, 收不到新版时, 从这里手动下最新版。

## 统计

| 项 | 数量 |
|---|---|
| 版本总数 | 296 |
| 线上可下载 | 296 (其中历史版本 235) |
| 仅本地 | 0 |

## 全部版本

| 版本 | 可下载 | 大小 | SHA256(前 16) | 说明 |
|---|---|---|---|---|
| 6.1-b2 | [下载](https://github.com/DongMenWeiQian/paperfmt-download/releases/download/v6.1-b2/paperfmt-v6.1-b2-setup.exe) | 39.6 MB | `F63A9157B4AFBF61` | 历史版本 |
| 6.2-b2 | [下载](https://github.com/DongMenWeiQian/paperfmt-download/releases/download/v6.2-b2/paperfmt-v6.2-b2-setup.exe) | 39.6 MB | `AF45671ADEAAA074` | 历史版本 |
| 6.4-b2 | [下载](https://github.com/DongMenWeiQian/paperfmt-download/releases/download/v6.4-b2/paperfmt-v6.4-b2-setup.exe) | 39.6 MB | `0ECDC9F56942D943` | 历史版本 |
| src-01_source_current | [下载](https://github.com/DongMenWeiQian/paperfmt-download/releases/download/src-01_source_current/source-01_source_current.old-b1274cd5e186.zip) | 22.5 MB | `B1274CD5E18671CE` | 历史版本 |
| src-02_source_v5_thesis_formatter | [下载](https://github.com/DongMenWeiQian/paperfmt-download/releases/download/src-02_source_v5_thesis_formatter/source-02_source_v5_thesis_formatter.zip) | 143.8 MB | `031F99F410146F25` | 历史版本 |
| src-03_memory_rules | [下载](https://github.com/DongMenWeiQian/paperfmt-download/releases/download/src-03_memory_rules/source-03_memory_rules.zip) | 2.6 MB | `093EF87017425394` | 历史版本 |
| src-04_backend_activation | [下载](https://github.com/DongMenWeiQian/paperfmt-download/releases/download/src-04_backend_activation/source-04_backend_activation.zip) | 10.8 MB | `D89503D6B2E0270F` | 历史版本 |
| src-05_dead_v664 | [下载](https://github.com/DongMenWeiQian/paperfmt-download/releases/download/src-05_dead_v664/source-05_dead_v664.zip) | 19.5 MB | `1977216C582F4987` | 历史版本 |
| src-05_session_workspace_v6 | [下载](https://github.com/DongMenWeiQian/paperfmt-download/releases/download/src-05_session_workspace_v6/source-05_session_workspace_v6.zip) | 138.2 MB | `D218C1BCE440E97C` | 历史版本 |
| src-06_installer_specs | [下载](https://github.com/DongMenWeiQian/paperfmt-download/releases/download/src-06_installer_specs/source-06_installer_specs.zip) | 0.0 MB | `8F7A16A20973ED33` | 历史版本 |
| src-07_docs_materials | [下载](https://github.com/DongMenWeiQian/paperfmt-download/releases/download/src-07_docs_materials/source-07_docs_materials.zip) | 32.7 MB | `7622E42B40D95E51` | 历史版本 |
| src-08_install_runtime_snapshot | [下载](https://github.com/DongMenWeiQian/paperfmt-download/releases/download/src-08_install_runtime_snapshot/source-08_install_runtime_snapshot.zip) | 13.4 MB | `90AA41ABB777B007` | 历史版本 |
| src-10_installers_v65x | [下载](https://github.com/DongMenWeiQian/paperfmt-download/releases/download/src-10_installers_v65x/source-10_installers_v65x.zip) | 45.5 MB | `48FCCB4B53C42F44` | 历史版本 |
| src-backup_v6562_broken_20261003 | [下载](https://github.com/DongMenWeiQian/paperfmt-download/releases/download/src-backup_v6562_broken_20261003/source-backup_v6562_broken_20261003.zip) | 0.0 MB | `EA121ED24AA3CA79` | 历史版本 |
| src-bad_pack_v6562_nofeat_20261003 | [下载](https://github.com/DongMenWeiQian/paperfmt-download/releases/download/src-bad_pack_v6562_nofeat_20261003/source-bad_pack_v6562_nofeat_20261003.zip) | 45.6 MB | `CF9C54601D199B44` | 历史版本 |
| src-e2e_6426_logs | [下载](https://github.com/DongMenWeiQian/paperfmt-download/releases/download/src-e2e_6426_logs/source-e2e_6426_logs.zip) | 0.9 MB | `791683FA61EC7916` | 历史版本 |
| src-e2e_6441 | [下载](https://github.com/DongMenWeiQian/paperfmt-download/releases/download/src-e2e_6441/source-e2e_6441.zip) | 0.0 MB | `084A86DE875FE490` | 历史版本 |
| src-e2e_v6439 | [下载](https://github.com/DongMenWeiQian/paperfmt-download/releases/download/src-e2e_v6439/source-e2e_v6439.zip) | 0.1 MB | `9927EA592AD0B3E0` | 历史版本 |
| src-index | [下载](https://github.com/DongMenWeiQian/paperfmt-download/releases/download/src-index/source-index.zip) | 0.0 MB | `454AFFC1C1F82AED` | 历史版本 |
| src-legacy_helpers | [下载](https://github.com/DongMenWeiQian/paperfmt-download/releases/download/src-legacy_helpers/source-legacy_helpers.zip) | 0.0 MB | `2CC0F0CCB49546CC` | 历史版本 |
| src-mem_backup_20261006 | [下载](https://github.com/DongMenWeiQian/paperfmt-download/releases/download/src-mem_backup_20261006/source-mem_backup_20261006.old-6fffb4f1ddc8.zip) | 0.0 MB | `6FFFB4F1DDC8A959` | 历史版本 |
| src-mem_backup_20261006_165632 | [下载](https://github.com/DongMenWeiQian/paperfmt-download/releases/download/src-mem_backup_20261006_165632/source-mem_backup_20261006_165632.zip) | 0.1 MB | `F3082D56540E6F5A` | 历史版本 |
| src-paperfmt-screenshots | [下载](https://github.com/DongMenWeiQian/paperfmt-download/releases/download/src-paperfmt-screenshots/source-paperfmt-screenshots.zip) | 0.0 MB | `8739C76E681F9009` | 历史版本 |
| src-patches | [下载](https://github.com/DongMenWeiQian/paperfmt-download/releases/download/src-patches/source-patches.old-9dea39b8aabc.zip) | 0.1 MB | `9DEA39B8AABC8539` | 历史版本 |
| src-splash_frames_v17_prev | [下载](https://github.com/DongMenWeiQian/paperfmt-download/releases/download/src-splash_frames_v17_prev/source-splash_frames_v17_prev.zip) | 2.7 MB | `2F531DF551E1D59C` | 历史版本 |
| src-test_scan_logs | [下载](https://github.com/DongMenWeiQian/paperfmt-download/releases/download/src-test_scan_logs/source-test_scan_logs.zip) | 6.2 MB | `0D7B1D591FE0098D` | 历史版本 |
| src-usercfg_before_e2e_20261006_182839 | [下载](https://github.com/DongMenWeiQian/paperfmt-download/releases/download/src-usercfg_before_e2e_20261006_182839/source-usercfg_before_e2e_20261006_182839.zip) | 0.0 MB | `CDB359A91A22FAA6` | 历史版本 |
| src-v6.6.1 | [下载](https://github.com/DongMenWeiQian/paperfmt-download/releases/download/src-v6.6.1/source-v6.6.1.zip) | 0.2 MB | `0E6FD806EB04A7B7` | 历史版本 |
| src-v6.6.13_prev | [下载](https://github.com/DongMenWeiQian/paperfmt-download/releases/download/src-v6.6.13_prev/source-v6.6.13_prev.zip) | 1.6 MB | `CF1128EE365E5D1F` | 历史版本 |
| src-v6.6.14_prev | [下载](https://github.com/DongMenWeiQian/paperfmt-download/releases/download/src-v6.6.14_prev/source-v6.6.14_prev.zip) | 0.1 MB | `079177DD8321E2DB` | 历史版本 |
| src-v6.6.15_prev | [下载](https://github.com/DongMenWeiQian/paperfmt-download/releases/download/src-v6.6.15_prev/source-v6.6.15_prev.zip) | 0.1 MB | `1CD3823BE06A84EC` | 历史版本 |
| src-v6.6.16_prev | [下载](https://github.com/DongMenWeiQian/paperfmt-download/releases/download/src-v6.6.16_prev/source-v6.6.16_prev.zip) | 0.2 MB | `47706B564C439757` | 历史版本 |
| src-v6.6.18_prev | [下载](https://github.com/DongMenWeiQian/paperfmt-download/releases/download/src-v6.6.18_prev/source-v6.6.18_prev.zip) | 0.0 MB | `9C1F9BB859176DCD` | 历史版本 |
| src-v6.6.19_prev | [下载](https://github.com/DongMenWeiQian/paperfmt-download/releases/download/src-v6.6.19_prev/source-v6.6.19_prev.zip) | 0.0 MB | `8739C76E681F9009` | 历史版本 |
| src-v6.6.2 | [下载](https://github.com/DongMenWeiQian/paperfmt-download/releases/download/src-v6.6.2/source-v6.6.2.zip) | 0.2 MB | `9BAA8C3AC9CE7C98` | 历史版本 |
| src-v6.6.20_prev | [下载](https://github.com/DongMenWeiQian/paperfmt-download/releases/download/src-v6.6.20_prev/source-v6.6.20_prev.zip) | 0.0 MB | `8739C76E681F9009` | 历史版本 |
| src-v6.6.21_prev | [下载](https://github.com/DongMenWeiQian/paperfmt-download/releases/download/src-v6.6.21_prev/source-v6.6.21_prev.zip) | 0.0 MB | `8739C76E681F9009` | 历史版本 |
| src-v6.6.22_prev | [下载](https://github.com/DongMenWeiQian/paperfmt-download/releases/download/src-v6.6.22_prev/source-v6.6.22_prev.zip) | 0.0 MB | `8739C76E681F9009` | 历史版本 |
| src-v6.6.24_prebuild | [下载](https://github.com/DongMenWeiQian/paperfmt-download/releases/download/src-v6.6.24_prebuild/source-v6.6.24_prebuild.zip) | 13.2 MB | `3E5DAD96E0DE63D7` | 历史版本 |
| src-v6.6.24_prev | [下载](https://github.com/DongMenWeiQian/paperfmt-download/releases/download/src-v6.6.24_prev/source-v6.6.24_prev.zip) | 0.0 MB | `8739C76E681F9009` | 历史版本 |
| src-v6.6.25_prebuild | [下载](https://github.com/DongMenWeiQian/paperfmt-download/releases/download/src-v6.6.25_prebuild/source-v6.6.25_prebuild.zip) | 13.2 MB | `B43952DDC6B1FE23` | 历史版本 |
| src-v6.6.25_prev | [下载](https://github.com/DongMenWeiQian/paperfmt-download/releases/download/src-v6.6.25_prev/source-v6.6.25_prev.zip) | 0.0 MB | `8739C76E681F9009` | 历史版本 |
| src-v6.6.26_prebuild | [下载](https://github.com/DongMenWeiQian/paperfmt-download/releases/download/src-v6.6.26_prebuild/source-v6.6.26_prebuild.zip) | 13.2 MB | `DF1888C906EBC267` | 历史版本 |
| src-v6.6.26_prev | [下载](https://github.com/DongMenWeiQian/paperfmt-download/releases/download/src-v6.6.26_prev/source-v6.6.26_prev.zip) | 0.0 MB | `8739C76E681F9009` | 历史版本 |
| src-v6.6.27_prebuild | [下载](https://github.com/DongMenWeiQian/paperfmt-download/releases/download/src-v6.6.27_prebuild/source-v6.6.27_prebuild.zip) | 13.2 MB | `AEC71E9207309BAF` | 历史版本 |
| src-v6.6.27_prev | [下载](https://github.com/DongMenWeiQian/paperfmt-download/releases/download/src-v6.6.27_prev/source-v6.6.27_prev.zip) | 0.0 MB | `8739C76E681F9009` | 历史版本 |
| src-v6.6.28_prebuild | [下载](https://github.com/DongMenWeiQian/paperfmt-download/releases/download/src-v6.6.28_prebuild/source-v6.6.28_prebuild.zip) | 13.2 MB | `9DFA5549F8E07435` | 历史版本 |
| src-v6.6.28_prev | [下载](https://github.com/DongMenWeiQian/paperfmt-download/releases/download/src-v6.6.28_prev/source-v6.6.28_prev.zip) | 0.0 MB | `8739C76E681F9009` | 历史版本 |
| src-v6.6.29_prebuild | [下载](https://github.com/DongMenWeiQian/paperfmt-download/releases/download/src-v6.6.29_prebuild/source-v6.6.29_prebuild.zip) | 13.2 MB | `41A8C37C7FE55DA6` | 历史版本 |
| src-v6.6.29_prev | [下载](https://github.com/DongMenWeiQian/paperfmt-download/releases/download/src-v6.6.29_prev/source-v6.6.29_prev.zip) | 0.0 MB | `8739C76E681F9009` | 历史版本 |
| src-v6.6.31 | [下载](https://github.com/DongMenWeiQian/paperfmt-download/releases/download/src-v6.6.31/source-v6.6.31.zip) | 0.0 MB | `8739C76E681F9009` | 历史版本 |
| src-v6.6.31_prebuild | [下载](https://github.com/DongMenWeiQian/paperfmt-download/releases/download/src-v6.6.31_prebuild/source-v6.6.31_prebuild.zip) | 13.2 MB | `61D83744FF95F9B3` | 历史版本 |
| src-v6.6.31_prev | [下载](https://github.com/DongMenWeiQian/paperfmt-download/releases/download/src-v6.6.31_prev/source-v6.6.31_prev.zip) | 0.0 MB | `8739C76E681F9009` | 历史版本 |
| src-v6.6.32 | [下载](https://github.com/DongMenWeiQian/paperfmt-download/releases/download/src-v6.6.32/source-v6.6.32.zip) | 0.0 MB | `8739C76E681F9009` | 历史版本 |
| src-v6.6.32_prebuild | [下载](https://github.com/DongMenWeiQian/paperfmt-download/releases/download/src-v6.6.32_prebuild/source-v6.6.32_prebuild.zip) | 13.2 MB | `839B9D2E07561D51` | 历史版本 |
| src-v6.6.32_prev | [下载](https://github.com/DongMenWeiQian/paperfmt-download/releases/download/src-v6.6.32_prev/source-v6.6.32_prev.zip) | 0.0 MB | `8739C76E681F9009` | 历史版本 |
| src-v6.6.33 | [下载](https://github.com/DongMenWeiQian/paperfmt-download/releases/download/src-v6.6.33/source-v6.6.33.zip) | 0.0 MB | `8739C76E681F9009` | 历史版本 |
| src-v6.6.33_prebuild | [下载](https://github.com/DongMenWeiQian/paperfmt-download/releases/download/src-v6.6.33_prebuild/source-v6.6.33_prebuild.zip) | 13.2 MB | `39077531547B4D1D` | 历史版本 |
| src-v6.6.33_prev | [下载](https://github.com/DongMenWeiQian/paperfmt-download/releases/download/src-v6.6.33_prev/source-v6.6.33_prev.zip) | 0.0 MB | `8739C76E681F9009` | 历史版本 |
| src-v6.6.34 | [下载](https://github.com/DongMenWeiQian/paperfmt-download/releases/download/src-v6.6.34/source-v6.6.34.zip) | 0.0 MB | `8739C76E681F9009` | 历史版本 |
| src-v6.6.34_prebuild | [下载](https://github.com/DongMenWeiQian/paperfmt-download/releases/download/src-v6.6.34_prebuild/source-v6.6.34_prebuild.zip) | 13.2 MB | `89A10A40DB064D59` | 历史版本 |
| src-v6.6.34_prev | [下载](https://github.com/DongMenWeiQian/paperfmt-download/releases/download/src-v6.6.34_prev/source-v6.6.34_prev.zip) | 0.0 MB | `8739C76E681F9009` | 历史版本 |
| src-v6.6.4_prev | [下载](https://github.com/DongMenWeiQian/paperfmt-download/releases/download/src-v6.6.4_prev/source-v6.6.4_prev.zip) | 133.0 MB | `923532DD90C9765B` | 历史版本 |
| src-v6.6.5_prev | [下载](https://github.com/DongMenWeiQian/paperfmt-download/releases/download/src-v6.6.5_prev/source-v6.6.5_prev.zip) | 44.2 MB | `AC0759AFE2FD71B8` | 历史版本 |
| src-v6.6.6_prev | [下载](https://github.com/DongMenWeiQian/paperfmt-download/releases/download/src-v6.6.6_prev/source-v6.6.6_prev.zip) | 3.2 MB | `73489C8E22C976CB` | 历史版本 |
| src-v6.6.7_prev | [下载](https://github.com/DongMenWeiQian/paperfmt-download/releases/download/src-v6.6.7_prev/source-v6.6.7_prev.zip) | 4.9 MB | `26921D246A846E38` | 历史版本 |
| src-v6.6.8_prev | [下载](https://github.com/DongMenWeiQian/paperfmt-download/releases/download/src-v6.6.8_prev/source-v6.6.8_prev.zip) | 57.2 MB | `A46F72775051945B` | 历史版本 |
| src-v7.0.0 | [下载](https://github.com/DongMenWeiQian/paperfmt-download/releases/download/src-v7.0.0/source-v7.0.0.zip) | 0.0 MB | `8739C76E681F9009` | 历史版本 |
| src-v7.0.0_prebuild | [下载](https://github.com/DongMenWeiQian/paperfmt-download/releases/download/src-v7.0.0_prebuild/source-v7.0.0_prebuild.zip) | 13.2 MB | `F5277E2B01C4A245` | 历史版本 |
| src-v7.0.0_prev | [下载](https://github.com/DongMenWeiQian/paperfmt-download/releases/download/src-v7.0.0_prev/source-v7.0.0_prev.zip) | 0.0 MB | `8739C76E681F9009` | 历史版本 |
| src-v7.0.1 | [下载](https://github.com/DongMenWeiQian/paperfmt-download/releases/download/src-v7.0.1/source-v7.0.1.zip) | 0.0 MB | `8739C76E681F9009` | 历史版本 |
| src-v7.0.1_prebuild | [下载](https://github.com/DongMenWeiQian/paperfmt-download/releases/download/src-v7.0.1_prebuild/source-v7.0.1_prebuild.zip) | 13.3 MB | `DAE4ED428D61E1FF` | 历史版本 |
| src-v7.0.1_prev | [下载](https://github.com/DongMenWeiQian/paperfmt-download/releases/download/src-v7.0.1_prev/source-v7.0.1_prev.zip) | 0.0 MB | `8739C76E681F9009` | 历史版本 |
| src-v7.0.2 | [下载](https://github.com/DongMenWeiQian/paperfmt-download/releases/download/src-v7.0.2/source-v7.0.2.zip) | 0.0 MB | `8739C76E681F9009` | 历史版本 |
| src-v7.0.2_prebuild | [下载](https://github.com/DongMenWeiQian/paperfmt-download/releases/download/src-v7.0.2_prebuild/source-v7.0.2_prebuild.zip) | 13.3 MB | `06CABEA91DA128FE` | 历史版本 |
| src-v7.0.2_prev | [下载](https://github.com/DongMenWeiQian/paperfmt-download/releases/download/src-v7.0.2_prev/source-v7.0.2_prev.zip) | 0.0 MB | `8739C76E681F9009` | 历史版本 |
| src-v7.0.3 | [下载](https://github.com/DongMenWeiQian/paperfmt-download/releases/download/src-v7.0.3/source-v7.0.3.zip) | 0.0 MB | `8739C76E681F9009` | 历史版本 |
| src-v7.0.3_prebuild | [下载](https://github.com/DongMenWeiQian/paperfmt-download/releases/download/src-v7.0.3_prebuild/source-v7.0.3_prebuild.zip) | 13.3 MB | `54F736E0B13A408F` | 历史版本 |
| src-v7.0.3_prev | [下载](https://github.com/DongMenWeiQian/paperfmt-download/releases/download/src-v7.0.3_prev/source-v7.0.3_prev.zip) | 0.0 MB | `8739C76E681F9009` | 历史版本 |
| src-v7.0.4 | [下载](https://github.com/DongMenWeiQian/paperfmt-download/releases/download/src-v7.0.4/source-v7.0.4.zip) | 0.0 MB | `8739C76E681F9009` | 历史版本 |
| src-v7.0.4_prebuild | [下载](https://github.com/DongMenWeiQian/paperfmt-download/releases/download/src-v7.0.4_prebuild/source-v7.0.4_prebuild.zip) | 13.3 MB | `ECF817BCD463DAC0` | 历史版本 |
| src-v7.0.4_prev | [下载](https://github.com/DongMenWeiQian/paperfmt-download/releases/download/src-v7.0.4_prev/source-v7.0.4_prev.zip) | 0.0 MB | `8739C76E681F9009` | 历史版本 |
| src-v7.1.0 | [下载](https://github.com/DongMenWeiQian/paperfmt-download/releases/download/src-v7.1.0/source-v7.1.0.zip) | 0.0 MB | `8739C76E681F9009` | 历史版本 |
| src-v7.1.0_prebuild | [下载](https://github.com/DongMenWeiQian/paperfmt-download/releases/download/src-v7.1.0_prebuild/source-v7.1.0_prebuild.zip) | 13.3 MB | `E5570093052D6205` | 历史版本 |
| src-v7.1.0_prev | [下载](https://github.com/DongMenWeiQian/paperfmt-download/releases/download/src-v7.1.0_prev/source-v7.1.0_prev.zip) | 0.0 MB | `8739C76E681F9009` | 历史版本 |
| src-v7.2.0 | [下载](https://github.com/DongMenWeiQian/paperfmt-download/releases/download/src-v7.2.0/source-v7.2.0.zip) | 0.0 MB | `8739C76E681F9009` | 历史版本 |
| src-v7.2.0_prebuild | [下载](https://github.com/DongMenWeiQian/paperfmt-download/releases/download/src-v7.2.0_prebuild/source-v7.2.0_prebuild.zip) | 13.3 MB | `F8E58F4EA191944E` | 历史版本 |
| src-v7.2.0_prev | [下载](https://github.com/DongMenWeiQian/paperfmt-download/releases/download/src-v7.2.0_prev/source-v7.2.0_prev.zip) | 0.0 MB | `8739C76E681F9009` | 历史版本 |
| src-v7.3.0 | [下载](https://github.com/DongMenWeiQian/paperfmt-download/releases/download/src-v7.3.0/source-v7.3.0.zip) | 0.0 MB | `8739C76E681F9009` | 历史版本 |
| src-v7.3.0_prebuild | [下载](https://github.com/DongMenWeiQian/paperfmt-download/releases/download/src-v7.3.0_prebuild/source-v7.3.0_prebuild.zip) | 13.3 MB | `68124EB2677F99D5` | 历史版本 |
| src-v7.3.0_prev | [下载](https://github.com/DongMenWeiQian/paperfmt-download/releases/download/src-v7.3.0_prev/source-v7.3.0_prev.zip) | 0.0 MB | `8739C76E681F9009` | 历史版本 |
| src-v7.3.1 | [下载](https://github.com/DongMenWeiQian/paperfmt-download/releases/download/src-v7.3.1/source-v7.3.1.zip) | 0.0 MB | `8739C76E681F9009` | 历史版本 |
| src-v7.3.1_prebuild | [下载](https://github.com/DongMenWeiQian/paperfmt-download/releases/download/src-v7.3.1_prebuild/source-v7.3.1_prebuild.zip) | 13.3 MB | `0BD5EA0281B2068C` | 历史版本 |
| src-v7.3.1_prev | [下载](https://github.com/DongMenWeiQian/paperfmt-download/releases/download/src-v7.3.1_prev/source-v7.3.1_prev.zip) | 0.0 MB | `8739C76E681F9009` | 历史版本 |
| src-v7.4.0_changelog_bug | [下载](https://github.com/DongMenWeiQian/paperfmt-download/releases/download/src-v7.4.0_changelog_bug/source-v7.4.0_changelog_bug.zip) | 45.8 MB | `4E835527AC921B0A` | 历史版本 |
| src-v7.4.0_prebuild | [下载](https://github.com/DongMenWeiQian/paperfmt-download/releases/download/src-v7.4.0_prebuild/source-v7.4.0_prebuild.zip) | 13.3 MB | `DB96DA07BB949EE6` | 历史版本 |
| src-v7.4.0_prev | [下载](https://github.com/DongMenWeiQian/paperfmt-download/releases/download/src-v7.4.0_prev/source-v7.4.0_prev.zip) | 0.0 MB | `8739C76E681F9009` | 历史版本 |
| src-v7.5.0_prebuild | [下载](https://github.com/DongMenWeiQian/paperfmt-download/releases/download/src-v7.5.0_prebuild/source-v7.5.0_prebuild.zip) | 13.3 MB | `1D729174EA0A0489` | 历史版本 |
| src-v7.5.0_prev | [下载](https://github.com/DongMenWeiQian/paperfmt-download/releases/download/src-v7.5.0_prev/source-v7.5.0_prev.zip) | 0.0 MB | `8739C76E681F9009` | 历史版本 |
| src-v7.5.1_prebuild | [下载](https://github.com/DongMenWeiQian/paperfmt-download/releases/download/src-v7.5.1_prebuild/source-v7.5.1_prebuild.zip) | 13.3 MB | `9D01EA93EB818FDD` | 历史版本 |
| src-v7.5.1_prev | [下载](https://github.com/DongMenWeiQian/paperfmt-download/releases/download/src-v7.5.1_prev/source-v7.5.1_prev.zip) | 0.0 MB | `8739C76E681F9009` | 历史版本 |
| src-v7.5.2_prebuild | [下载](https://github.com/DongMenWeiQian/paperfmt-download/releases/download/src-v7.5.2_prebuild/source-v7.5.2_prebuild.zip) | 13.4 MB | `C15C413762915BF7` | 历史版本 |
| src-v7.5.2_prev | [下载](https://github.com/DongMenWeiQian/paperfmt-download/releases/download/src-v7.5.2_prev/source-v7.5.2_prev.zip) | 0.0 MB | `8739C76E681F9009` | 历史版本 |
| src-v7.5.3_prebuild | [下载](https://github.com/DongMenWeiQian/paperfmt-download/releases/download/src-v7.5.3_prebuild/source-v7.5.3_prebuild.zip) | 13.4 MB | `B6D8E671B554E243` | 历史版本 |
| src-v7.5.3_prev | [下载](https://github.com/DongMenWeiQian/paperfmt-download/releases/download/src-v7.5.3_prev/source-v7.5.3_prev.zip) | 0.0 MB | `8739C76E681F9009` | 历史版本 |
| src-v7.5.4_prebuild | [下载](https://github.com/DongMenWeiQian/paperfmt-download/releases/download/src-v7.5.4_prebuild/source-v7.5.4_prebuild.zip) | 13.4 MB | `CAF3BC12E2E3F976` | 历史版本 |
| src-v7.5.4_prev | [下载](https://github.com/DongMenWeiQian/paperfmt-download/releases/download/src-v7.5.4_prev/source-v7.5.4_prev.zip) | 0.0 MB | `8739C76E681F9009` | 历史版本 |
| src-v7.5.5_prebuild | [下载](https://github.com/DongMenWeiQian/paperfmt-download/releases/download/src-v7.5.5_prebuild/source-v7.5.5_prebuild.zip) | 13.4 MB | `7CCED394BC570F5A` | 历史版本 |
| src-v7.5.5_prev | [下载](https://github.com/DongMenWeiQian/paperfmt-download/releases/download/src-v7.5.5_prev/source-v7.5.5_prev.zip) | 0.0 MB | `8739C76E681F9009` | 历史版本 |
| src-v7.6.0_prebuild | [下载](https://github.com/DongMenWeiQian/paperfmt-download/releases/download/src-v7.6.0_prebuild/source-v7.6.0_prebuild.zip) | 13.5 MB | `5F015385D97F92C2` | 历史版本 |
| src-v7.6.0_prev | [下载](https://github.com/DongMenWeiQian/paperfmt-download/releases/download/src-v7.6.0_prev/source-v7.6.0_prev.zip) | 0.0 MB | `8739C76E681F9009` | 历史版本 |
| src-v7.7.0_compat_pre | [下载](https://github.com/DongMenWeiQian/paperfmt-download/releases/download/src-v7.7.0_compat_pre/source-v7.7.0_compat_pre.zip) | 14.1 MB | `305F7C1A7D5A6D81` | 历史版本 |
| src-v7.7.0_prebuild | [下载](https://github.com/DongMenWeiQian/paperfmt-download/releases/download/src-v7.7.0_prebuild/source-v7.7.0_prebuild.zip) | 13.5 MB | `8BBE65790738FE8F` | 历史版本 |
| src-v7.7.0_prev | [下载](https://github.com/DongMenWeiQian/paperfmt-download/releases/download/src-v7.7.0_prev/source-v7.7.0_prev.zip) | 0.0 MB | `8739C76E681F9009` | 历史版本 |
| src-v7.7.0_tabs_pre | [下载](https://github.com/DongMenWeiQian/paperfmt-download/releases/download/src-v7.7.0_tabs_pre/source-v7.7.0_tabs_pre.zip) | 0.1 MB | `E7065274691D2C21` | 历史版本 |
| src-v7.7.10_prebuild | [下载](https://github.com/DongMenWeiQian/paperfmt-download/releases/download/src-v7.7.10_prebuild/source-v7.7.10_prebuild.zip) | 13.4 MB | `14080984418FEB74` | 历史版本 |
| src-v7.7.11_prebuild | [下载](https://github.com/DongMenWeiQian/paperfmt-download/releases/download/src-v7.7.11_prebuild/source-v7.7.11_prebuild.zip) | 13.4 MB | `A7E7C007027CCAB8` | 历史版本 |
| src-v7.7.12_prebuild | [下载](https://github.com/DongMenWeiQian/paperfmt-download/releases/download/src-v7.7.12_prebuild/source-v7.7.12_prebuild.zip) | 13.4 MB | `06A7DEEADBCE8F02` | 历史版本 |
| src-v7.7.13_prebuild | [下载](https://github.com/DongMenWeiQian/paperfmt-download/releases/download/src-v7.7.13_prebuild/source-v7.7.13_prebuild.zip) | 13.4 MB | `C5003F8DFCF8128D` | 历史版本 |
| src-v7.7.14_prebuild | [下载](https://github.com/DongMenWeiQian/paperfmt-download/releases/download/src-v7.7.14_prebuild/source-v7.7.14_prebuild.zip) | 13.4 MB | `48136E63C12144D8` | 历史版本 |
| src-v7.7.15_prebuild | [下载](https://github.com/DongMenWeiQian/paperfmt-download/releases/download/src-v7.7.15_prebuild/source-v7.7.15_prebuild.zip) | 13.5 MB | `35F02455E995A414` | 历史版本 |
| src-v7.7.16_prebuild | [下载](https://github.com/DongMenWeiQian/paperfmt-download/releases/download/src-v7.7.16_prebuild/source-v7.7.16_prebuild.zip) | 13.5 MB | `5361EDF9BBA5B340` | 历史版本 |
| src-v7.7.1_prev | [下载](https://github.com/DongMenWeiQian/paperfmt-download/releases/download/src-v7.7.1_prev/source-v7.7.1_prev.zip) | 0.0 MB | `8739C76E681F9009` | 历史版本 |
| src-v7.7.2_prev | [下载](https://github.com/DongMenWeiQian/paperfmt-download/releases/download/src-v7.7.2_prev/source-v7.7.2_prev.zip) | 0.0 MB | `8739C76E681F9009` | 历史版本 |
| src-v7.7.4_prebuild | [下载](https://github.com/DongMenWeiQian/paperfmt-download/releases/download/src-v7.7.4_prebuild/source-v7.7.4_prebuild.zip) | 13.7 MB | `F816CFC2081D3044` | 历史版本 |
| src-v7.7.4_prev | [下载](https://github.com/DongMenWeiQian/paperfmt-download/releases/download/src-v7.7.4_prev/source-v7.7.4_prev.zip) | 0.0 MB | `8739C76E681F9009` | 历史版本 |
| src-v7.7.5_prebuild | [下载](https://github.com/DongMenWeiQian/paperfmt-download/releases/download/src-v7.7.5_prebuild/source-v7.7.5_prebuild.old-a16060a371c7.zip) | 13.7 MB | `A16060A371C7EEFB` | 历史版本 |
| src-v7.7.5_prev | [下载](https://github.com/DongMenWeiQian/paperfmt-download/releases/download/src-v7.7.5_prev/source-v7.7.5_prev.zip) | 0.0 MB | `8739C76E681F9009` | 历史版本 |
| src-v7.7.6_prebuild | [下载](https://github.com/DongMenWeiQian/paperfmt-download/releases/download/src-v7.7.6_prebuild/source-v7.7.6_prebuild.old-9e0aabedd64a.zip) | 13.7 MB | `9E0AABEDD64A0DC8` | 历史版本 |
| src-v7.7.6_prev | [下载](https://github.com/DongMenWeiQian/paperfmt-download/releases/download/src-v7.7.6_prev/source-v7.7.6_prev.zip) | 45.9 MB | `167D76BBDF99EB83` | 历史版本 |
| src-v7.7.7_prebuild | [下载](https://github.com/DongMenWeiQian/paperfmt-download/releases/download/src-v7.7.7_prebuild/source-v7.7.7_prebuild.old-9e8b6b4792b5.zip) | 13.7 MB | `9E8B6B4792B5984A` | 历史版本 |
| src-v7.7.7_prev | [下载](https://github.com/DongMenWeiQian/paperfmt-download/releases/download/src-v7.7.7_prev/source-v7.7.7_prev.zip) | 45.9 MB | `A5ADF0513520CFFF` | 历史版本 |
| src-v7.7.8_prebuild | [下载](https://github.com/DongMenWeiQian/paperfmt-download/releases/download/src-v7.7.8_prebuild/source-v7.7.8_prebuild.old-fbfbc43860b6.zip) | 13.7 MB | `FBFBC43860B6FC8D` | 历史版本 |
| src-v7.7.8_prev | [下载](https://github.com/DongMenWeiQian/paperfmt-download/releases/download/src-v7.7.8_prev/source-v7.7.8_prev.zip) | 45.9 MB | `BC42A461BE8BD1FE` | 历史版本 |
| src-v7.7.9_prebuild | [下载](https://github.com/DongMenWeiQian/paperfmt-download/releases/download/src-v7.7.9_prebuild/source-v7.7.9_prebuild.old-426e01205f54.zip) | 13.8 MB | `426E01205F54E5BE` | 历史版本 |
| src-误标_原v6.6.22_prebuild_实为6.6.24源码_20261008 | [下载](https://github.com/DongMenWeiQian/paperfmt-download/releases/download/src-%E8%AF%AF%E6%A0%87_%E5%8E%9Fv6.6.22_prebuild_%E5%AE%9E%E4%B8%BA6.6.24%E6%BA%90%E7%A0%81_20261008/source-._.v6.6.22_prebuild_.6.6.24._20261008.zip) | 13.2 MB | `3E5DAD96E0DE63D7` | 历史版本 |
| 6.1 | [下载](https://github.com/DongMenWeiQian/paperfmt-download/releases/download/v6.1/paperfmt-v6.1-setup.exe) | 37.8 MB | `863B0C6B17E4D7CE` | 历史版本 |
| 6.2 | [下载](https://github.com/DongMenWeiQian/paperfmt-download/releases/download/v6.2/paperfmt-v6.2-setup.exe) | 39.5 MB | `74D44E70F419A5C2` | 历史版本 |
| 6.2.1 | [下载](https://github.com/DongMenWeiQian/paperfmt-download/releases/download/v6.2.1/paperfmt-v6.2.1-setup.exe) | 39.5 MB | `241A0851B2981FFB` | 历史版本 |
| 6.2.2 | [下载](https://github.com/DongMenWeiQian/paperfmt-download/releases/download/v6.2.2/paperfmt-v6.2.2-setup.exe) | 39.5 MB | `684136958B436165` | 历史版本 |
| 6.2.3 | [下载](https://github.com/DongMenWeiQian/paperfmt-download/releases/download/v6.2.3/paperfmt-v6.2.3-setup.exe) | 39.5 MB | `9F51166223C416D0` | 历史版本 |
| 6.2.4 | [下载](https://github.com/DongMenWeiQian/paperfmt-download/releases/download/v6.2.4/paperfmt-v6.2.4-setup.exe) | 39.5 MB | `44FF3FAA5EC7F7A3` | 历史版本 |
| 6.2.5 | [下载](https://github.com/DongMenWeiQian/paperfmt-download/releases/download/v6.2.5/paperfmt-v6.2.5-setup.exe) | 39.5 MB | `4877F47632D23CB8` | 历史版本 |
| 6.2.6 | [下载](https://github.com/DongMenWeiQian/paperfmt-download/releases/download/v6.2.6/paperfmt-v6.2.6-setup.exe) | 39.5 MB | `2D3E64E945CEB72E` | 历史版本 |
| 6.2.8 | [下载](https://github.com/DongMenWeiQian/paperfmt-download/releases/download/v6.2.8/paperfmt-v6.2.8-setup.exe) | 39.6 MB | `77AE152C6C8E29D1` | 历史版本 |
| 6.2.9 | [下载](https://github.com/DongMenWeiQian/paperfmt-download/releases/download/v6.2.9/paperfmt-v6.2.9-setup.exe) | 39.6 MB | `6D9024FD6439FE11` | 历史版本 |
| 6.2.10 | [下载](https://github.com/DongMenWeiQian/paperfmt-download/releases/download/v6.2.10/paperfmt-v6.2.10-setup.exe) | 39.6 MB | `61BF8B310692DCC0` | 历史版本 |
| 6.2.11 | [下载](https://github.com/DongMenWeiQian/paperfmt-download/releases/download/v6.2.11/paperfmt-v6.2.11-setup.exe) | 39.6 MB | `C2A9F52A74380FBE` | 历史版本 |
| 6.3 | [下载](https://github.com/DongMenWeiQian/paperfmt-download/releases/download/v6.3/paperfmt-v6.3-setup.exe) | 39.6 MB | `B0F7613C94385D3D` | 历史版本 |
| 6.4 | [下载](https://github.com/DongMenWeiQian/paperfmt-download/releases/download/v6.4/paperfmt-v6.4-setup.exe) | 39.6 MB | `8D8339503A63EA3B` | 历史版本 |
| 6.4.1 | [下载](https://github.com/DongMenWeiQian/paperfmt-download/releases/download/v6.4.1/paperfmt-v6.4.1-setup.exe) | 33.4 MB | `CC2E98C5F9B5E549` | 历史版本 |
| 6.4.18 | [下载](https://github.com/DongMenWeiQian/paperfmt-download/releases/download/v6.4.18/paperfmt-v6.4.18-setup.exe) | 37.5 MB | `422C676617E2F57D` | 历史版本 |
| 6.4.24 | [下载](https://github.com/DongMenWeiQian/paperfmt-download/releases/download/v6.4.24/paperfmt-v6.4.24-setup.exe) | 46.2 MB | `8C067702D6774E90` | 历史版本 |
| 6.4.25 | [下载](https://github.com/DongMenWeiQian/paperfmt-download/releases/download/v6.4.25/paperfmt-v6.4.25-setup.exe) | 46.2 MB | `749102DE758F6306` | 历史版本 |
| 6.4.26 | [下载](https://github.com/DongMenWeiQian/paperfmt-download/releases/download/v6.4.26/paperfmt-v6.4.26-setup.exe) | 46.2 MB | `A8A634682BA508A9` | 历史版本 |
| 6.4.27 | [下载](https://github.com/DongMenWeiQian/paperfmt-download/releases/download/v6.4.27/paperfmt-v6.4.27-setup.exe) | 46.2 MB | `585CCC6E26635D83` | 历史版本 |
| 6.4.28 | [下载](https://github.com/DongMenWeiQian/paperfmt-download/releases/download/v6.4.28/paperfmt-v6.4.28-setup.exe) | 46.2 MB | `32748AE0AEC2DCD8` | 历史版本 |
| 6.4.29 | [下载](https://github.com/DongMenWeiQian/paperfmt-download/releases/download/v6.4.29/paperfmt-v6.4.29-setup.exe) | 46.2 MB | `CB91441EE9754B3B` | 历史版本 |
| 6.4.30 | [下载](https://github.com/DongMenWeiQian/paperfmt-download/releases/download/v6.4.30/paperfmt-v6.4.30-setup.exe) | 46.2 MB | `5924877F1FE33204` | 历史版本 |
| 6.4.31 | [下载](https://github.com/DongMenWeiQian/paperfmt-download/releases/download/v6.4.31/paperfmt-v6.4.31-setup.exe) | 46.2 MB | `E3857394ADBFEC42` | 历史版本 |
| 6.4.32 | [下载](https://github.com/DongMenWeiQian/paperfmt-download/releases/download/v6.4.32/paperfmt-v6.4.32-setup.exe) | 46.2 MB | `D0B338A6C6772208` | 历史版本 |
| 6.4.33 | [下载](https://github.com/DongMenWeiQian/paperfmt-download/releases/download/v6.4.33/paperfmt-v6.4.33-setup.exe) | 46.2 MB | `410A145841965BE1` | 历史版本 |
| 6.4.34 | [下载](https://github.com/DongMenWeiQian/paperfmt-download/releases/download/v6.4.34/paperfmt-v6.4.34-setup.exe) | 46.2 MB | `FF1CEBD037A26268` | 历史版本 |
| 6.4.35 | [下载](https://github.com/DongMenWeiQian/paperfmt-download/releases/download/v6.4.35/paperfmt-v6.4.35-setup.exe) | 46.2 MB | `42470AC6C2630C56` | 历史版本 |
| 6.4.36 | [下载](https://github.com/DongMenWeiQian/paperfmt-download/releases/download/v6.4.36/paperfmt-v6.4.36-setup.exe) | 46.2 MB | `E380B1FBE39BDFB2` | 历史版本 |
| 6.4.37 | [下载](https://github.com/DongMenWeiQian/paperfmt-download/releases/download/v6.4.37/paperfmt-v6.4.37-setup.exe) | 46.2 MB | `8487D52EFE8C9130` | 历史版本 |
| 6.4.38 | [下载](https://github.com/DongMenWeiQian/paperfmt-download/releases/download/v6.4.38/paperfmt-v6.4.38-setup.exe) | 46.2 MB | `AC230779A9CE7A20` | 历史版本 |
| 6.4.39 | [下载](https://github.com/DongMenWeiQian/paperfmt-download/releases/download/v6.4.39/paperfmt-v6.4.39-setup.exe) | 46.2 MB | `F2A4B9F56D0735CF` | 历史版本 |
| 6.4.40 | [下载](https://github.com/DongMenWeiQian/paperfmt-download/releases/download/v6.4.40/paperfmt-v6.4.40-setup.exe) | 46.2 MB | `EF3EADCFBBDD6251` | 历史版本 |
| 6.4.41 | [下载](https://github.com/DongMenWeiQian/paperfmt-download/releases/download/v6.4.41/paperfmt-v6.4.41-setup.exe) | 46.2 MB | `1E478589A55A86FE` | 历史版本 |
| 6.4.42 | [下载](https://github.com/DongMenWeiQian/paperfmt-download/releases/download/v6.4.42/paperfmt-v6.4.42-setup.exe) | 46.2 MB | `B11C142EC5FF1D75` | 历史版本 |
| 6.4.43 | [下载](https://github.com/DongMenWeiQian/paperfmt-download/releases/download/v6.4.43/paperfmt-v6.4.43-setup.exe) | 46.2 MB | `C35A9912E44278BB` | 历史版本 |
| 6.4.44 | [下载](https://github.com/DongMenWeiQian/paperfmt-download/releases/download/v6.4.44/paperfmt-v6.4.44-setup.exe) | 46.2 MB | `15472B4C25FCECF2` | 历史版本 |
| 6.4.45 | [下载](https://github.com/DongMenWeiQian/paperfmt-download/releases/download/v6.4.45/paperfmt-v6.4.45-setup.exe) | 46.2 MB | `234C49A52199E175` | 历史版本 |
| 6.4.47 | [下载](https://github.com/DongMenWeiQian/paperfmt-download/releases/download/v6.4.47/paperfmt-v6.4.47-setup.exe) | 46.2 MB | `68534C1EF8B65EC9` | 历史版本 |
| 6.5.7 | [下载](https://github.com/DongMenWeiQian/paperfmt-download/releases/download/v6.5.7/paperfmt-v6.5.7-setup.exe) | 46.2 MB | `4415BDCC1C9A9D81` | 历史版本 |
| 6.5.8 | [下载](https://github.com/DongMenWeiQian/paperfmt-download/releases/download/v6.5.8/paperfmt-v6.5.8-setup.exe) | 46.3 MB | `6B67B5D158791100` | 历史版本 |
| 6.5.9 | [下载](https://github.com/DongMenWeiQian/paperfmt-download/releases/download/v6.5.9/paperfmt-v6.5.9-setup.exe) | 46.3 MB | `E7C19ABEEDE521FF` | 历史版本 |
| 6.5.10 | [下载](https://github.com/DongMenWeiQian/paperfmt-download/releases/download/v6.5.10/paperfmt-v6.5.10-setup.exe) | 46.3 MB | `32EE399CFFC5CDE9` | 历史版本 |
| 6.5.11 | [下载](https://github.com/DongMenWeiQian/paperfmt-download/releases/download/v6.5.11/paperfmt-v6.5.11-setup.exe) | 46.3 MB | `6E7555EE93A9F274` | 历史版本 |
| 6.5.12 | [下载](https://github.com/DongMenWeiQian/paperfmt-download/releases/download/v6.5.12/paperfmt-v6.5.12-setup.exe) | 46.3 MB | `FB150700DE43F78C` | 历史版本 |
| 6.5.13 | [下载](https://github.com/DongMenWeiQian/paperfmt-download/releases/download/v6.5.13/paperfmt-v6.5.13-setup.exe) | 46.3 MB | `2126C6E3F95F5646` | 历史版本 |
| 6.5.14 | [下载](https://github.com/DongMenWeiQian/paperfmt-download/releases/download/v6.5.14/paperfmt-v6.5.14-setup.exe) | 46.3 MB | `49473B5415610FC5` | 历史版本 |
| 6.5.15 | [下载](https://github.com/DongMenWeiQian/paperfmt-download/releases/download/v6.5.15/paperfmt-v6.5.15-setup.exe) | 46.3 MB | `68A618D10922DCB2` | 历史版本 |
| 6.5.16 | [下载](https://github.com/DongMenWeiQian/paperfmt-download/releases/download/v6.5.16/paperfmt-v6.5.16-setup.exe) | 46.3 MB | `3B018D5660C481BB` | 历史版本 |
| 6.5.17 | [下载](https://github.com/DongMenWeiQian/paperfmt-download/releases/download/v6.5.17/paperfmt-v6.5.17-setup.exe) | 46.3 MB | `3F2A9B1CFB5549D9` | 历史版本 |
| 6.5.18 | [下载](https://github.com/DongMenWeiQian/paperfmt-download/releases/download/v6.5.18/paperfmt-v6.5.18-setup.exe) | 46.3 MB | `CE8A6E53BEE36D0A` | 历史版本 |
| 6.5.19 | [下载](https://github.com/DongMenWeiQian/paperfmt-download/releases/download/v6.5.19/paperfmt-v6.5.19-setup.exe) | 46.3 MB | `4A0EBDE1BBDA556E` | 历史版本 |
| 6.5.20 | [下载](https://github.com/DongMenWeiQian/paperfmt-download/releases/download/v6.5.20/paperfmt-v6.5.20-setup.exe) | 46.3 MB | `C8886F7FC5D447EA` | 历史版本 |
| 6.5.21 | [下载](https://github.com/DongMenWeiQian/paperfmt-download/releases/download/v6.5.21/paperfmt-v6.5.21-setup.exe) | 46.3 MB | `9907C75477778A7C` | 历史版本 |
| 6.5.22 | [下载](https://github.com/DongMenWeiQian/paperfmt-download/releases/download/v6.5.22/paperfmt-v6.5.22-setup.exe) | 46.3 MB | `50080B891E04F5C4` | 历史版本 |
| 6.5.23 | [下载](https://github.com/DongMenWeiQian/paperfmt-download/releases/download/v6.5.23/paperfmt-v6.5.23-setup.exe) | 46.3 MB | `826C278D33DCB4DA` | 历史版本 |
| 6.5.24 | [下载](https://github.com/DongMenWeiQian/paperfmt-download/releases/download/v6.5.24/paperfmt-v6.5.24-setup.exe) | 46.3 MB | `04B4E710ED6F825E` | 历史版本 |
| 6.5.25 | [下载](https://github.com/DongMenWeiQian/paperfmt-download/releases/download/v6.5.25/paperfmt-v6.5.25-setup.exe) | 46.3 MB | `A9BA913665BECD3F` | 历史版本 |
| 6.5.26 | [下载](https://github.com/DongMenWeiQian/paperfmt-download/releases/download/v6.5.26/paperfmt-v6.5.26-setup.exe) | 46.3 MB | `08B2C29C4FD1C108` | 历史版本 |
| 6.5.27 | [下载](https://github.com/DongMenWeiQian/paperfmt-download/releases/download/v6.5.27/paperfmt-v6.5.27-setup.exe) | 46.3 MB | `9D41CFA5DDA62192` | 历史版本 |
| 6.5.28 | [下载](https://github.com/DongMenWeiQian/paperfmt-download/releases/download/v6.5.28/paperfmt-v6.5.28-setup.exe) | 46.3 MB | `3CD376EA20249697` | 历史版本 |
| 6.5.29 | [下载](https://github.com/DongMenWeiQian/paperfmt-download/releases/download/v6.5.29/paperfmt-v6.5.29-setup.exe) | 46.3 MB | `996EAD1B73563DB8` | 历史版本 |
| 6.5.30 | [下载](https://github.com/DongMenWeiQian/paperfmt-download/releases/download/v6.5.30/paperfmt-v6.5.30-setup.exe) | 46.3 MB | `081F88A9650ADD39` | 历史版本 |
| 6.5.31 | [下载](https://github.com/DongMenWeiQian/paperfmt-download/releases/download/v6.5.31/paperfmt-v6.5.31-setup.exe) | 46.3 MB | `901364BDC5304C18` | 历史版本 |
| 6.5.32 | [下载](https://github.com/DongMenWeiQian/paperfmt-download/releases/download/v6.5.32/paperfmt-v6.5.32-setup.exe) | 46.3 MB | `9891BE21052746C0` | 历史版本 |
| 6.5.33 | [下载](https://github.com/DongMenWeiQian/paperfmt-download/releases/download/v6.5.33/paperfmt-v6.5.33-setup.exe) | 46.3 MB | `2BC3F39808CA13BD` | 历史版本 |
| 6.5.34 | [下载](https://github.com/DongMenWeiQian/paperfmt-download/releases/download/v6.5.34/paperfmt-v6.5.34-setup.exe) | 46.3 MB | `1C91CF0D48A74AA8` | 历史版本 |
| 6.5.35 | [下载](https://github.com/DongMenWeiQian/paperfmt-download/releases/download/v6.5.35/paperfmt-v6.5.35-setup.exe) | 46.3 MB | `67D5D416E3C25FE9` | 历史版本 |
| 6.5.36 | [下载](https://github.com/DongMenWeiQian/paperfmt-download/releases/download/v6.5.36/paperfmt-v6.5.36-setup.exe) | 46.3 MB | `552C60E086F9E165` | 历史版本 |
| 6.5.37 | [下载](https://github.com/DongMenWeiQian/paperfmt-download/releases/download/v6.5.37/paperfmt-v6.5.37-setup.exe) | 46.3 MB | `04E3FAB51B4F585C` | 历史版本 |
| 6.5.38 | [下载](https://github.com/DongMenWeiQian/paperfmt-download/releases/download/v6.5.38/paperfmt-v6.5.38-setup.exe) | 46.3 MB | `7D4CF590C9E132BF` | 历史版本 |
| 6.5.39 | [下载](https://github.com/DongMenWeiQian/paperfmt-download/releases/download/v6.5.39/paperfmt-v6.5.39-setup.exe) | 46.3 MB | `5E641B01860B4AE6` | 历史版本 |
| 6.5.40 | [下载](https://github.com/DongMenWeiQian/paperfmt-download/releases/download/v6.5.40/paperfmt-v6.5.40-setup.exe) | 46.3 MB | `21A4BDCFD2D3F185` | 历史版本 |
| 6.5.41 | [下载](https://github.com/DongMenWeiQian/paperfmt-download/releases/download/v6.5.41/paperfmt-v6.5.41-setup.exe) | 46.3 MB | `4DC96DC2B8D41E82` | 历史版本 |
| 6.5.43 | [下载](https://github.com/DongMenWeiQian/paperfmt-download/releases/download/v6.5.43/paperfmt-v6.5.43-setup.exe) | 46.3 MB | `2A76C232F00CD4A0` | 历史版本 |
| 6.5.44 | [下载](https://github.com/DongMenWeiQian/paperfmt-download/releases/download/v6.5.44/paperfmt-v6.5.44-setup.exe) | 46.3 MB | `1534416719DF6665` | 历史版本 |
| 6.5.45 | [下载](https://github.com/DongMenWeiQian/paperfmt-download/releases/download/v6.5.45/paperfmt-v6.5.45-setup.exe) | 46.3 MB | `B1DBD0F0DED119C4` | 历史版本 |
| 6.5.46 | [下载](https://github.com/DongMenWeiQian/paperfmt-download/releases/download/v6.5.46/paperfmt-v6.5.46-setup.exe) | 46.3 MB | `07D44269E1412B57` | 历史版本 |
| 6.5.47 | [下载](https://github.com/DongMenWeiQian/paperfmt-download/releases/download/v6.5.47/paperfmt-v6.5.47-setup.exe) | 46.3 MB | `905C079B8B306BB7` | 历史版本 |
| 6.5.48 | [下载](https://github.com/DongMenWeiQian/paperfmt-download/releases/download/v6.5.48/paperfmt-v6.5.48-setup.exe) | 46.3 MB | `461C84512A8989C8` | 历史版本 |
| 6.5.49 | [下载](https://github.com/DongMenWeiQian/paperfmt-download/releases/download/v6.5.49/paperfmt-v6.5.49-setup.exe) | 46.3 MB | `53C2C9B07C136113` | 历史版本 |
| 6.5.50 | [下载](https://github.com/DongMenWeiQian/paperfmt-download/releases/download/v6.5.50/paperfmt-v6.5.50-setup.exe) | 46.3 MB | `5F5B3AA5CA36209C` | 历史版本 |
| 6.5.51 | [下载](https://github.com/DongMenWeiQian/paperfmt-download/releases/download/v6.5.51/paperfmt-v6.5.51-setup.exe) | 46.3 MB | `300C9B2D70E7209F` | 历史版本 |
| 6.5.52 | [下载](https://github.com/DongMenWeiQian/paperfmt-download/releases/download/v6.5.52/paperfmt-v6.5.52-setup.exe) | 46.3 MB | `4530F0218F88F2CF` | 历史版本 |
| 6.5.53 | [下载](https://github.com/DongMenWeiQian/paperfmt-download/releases/download/v6.5.53/paperfmt-v6.5.53-setup.exe) | 46.3 MB | `7B051B26E1DAA0A0` | 历史版本 |
| 6.5.54 | [下载](https://github.com/DongMenWeiQian/paperfmt-download/releases/download/v6.5.54/paperfmt-v6.5.54-setup.exe) | 46.3 MB | `A1D46073F9171BA4` | 历史版本 |
| 6.5.55 | [下载](https://github.com/DongMenWeiQian/paperfmt-download/releases/download/v6.5.55/paperfmt-v6.5.55-setup.exe) | 46.3 MB | `18E43819231DCB63` | 历史版本 |
| 6.5.56 | [下载](https://github.com/DongMenWeiQian/paperfmt-download/releases/download/v6.5.56/paperfmt-v6.5.56-setup.exe) | 46.3 MB | `21244CB231663463` | 历史版本 |
| 6.5.57 | [下载](https://github.com/DongMenWeiQian/paperfmt-download/releases/download/v6.5.57/paperfmt-v6.5.57-setup.exe) | 46.3 MB | `7EB69997E8929B79` | 历史版本 |
| 6.5.58 | [下载](https://github.com/DongMenWeiQian/paperfmt-download/releases/download/v6.5.58/paperfmt-v6.5.58-setup.exe) | 46.3 MB | `D6101E9F22646445` | 历史版本 |
| 6.5.59 | [下载](https://github.com/DongMenWeiQian/paperfmt-download/releases/download/v6.5.59/paperfmt-v6.5.59-setup.exe) | 46.3 MB | `25BCC1C5F3E92905` | 历史版本 |
| 6.5.60 | [下载](https://github.com/DongMenWeiQian/paperfmt-download/releases/download/v6.5.60/paperfmt-v6.5.60-setup.exe) | 46.3 MB | `05B2B7528C5D9A3B` | 历史版本 |
| 6.5.61 | [下载](https://github.com/DongMenWeiQian/paperfmt-download/releases/download/v6.5.61/paperfmt-v6.5.61-setup.exe) | 46.3 MB | `4DE874A0514B30BE` | 历史版本 |
| 6.5.62 | [下载](https://github.com/DongMenWeiQian/paperfmt-download/releases/download/v6.5.62/paperfmt-v6.5.62-setup.exe) | 46.3 MB | `30702DD4838FE1F1` | 历史版本 |
| 6.6.0 | [下载](https://github.com/DongMenWeiQian/paperfmt-download/releases/download/v6.6.0/paperfmt-v6.6.0-setup.exe) | 46.3 MB | `A20AE93C4B25A840` | 历史版本 |
| 6.6.1 | [下载](https://github.com/DongMenWeiQian/paperfmt-download/releases/download/v6.6.1/paperfmt-v6.6.1-setup.exe) | 46.3 MB | `CA88E69B1BF3247A` | 历史版本 |
| 6.6.2 | [下载](https://github.com/DongMenWeiQian/paperfmt-download/releases/download/v6.6.2/paperfmt-v6.6.2-setup.exe) | 46.4 MB | `1ED3911BC7472F51` | 历史版本 |
| 6.6.3 | [下载](https://github.com/DongMenWeiQian/paperfmt-download/releases/download/v6.6.3/paperfmt-v6.6.3-setup.exe) | 46.4 MB | `0AB4D5E42C8B6A65` | 历史版本 |
| 6.6.4 | [下载](https://github.com/DongMenWeiQian/paperfmt-download/releases/download/v6.6.4/paperfmt-v6.6.4-setup.exe) | 40.2 MB | `0BFA3FB0CE2ED64F` |  |
| 6.6.5 | [下载](https://github.com/DongMenWeiQian/paperfmt-download/releases/download/v6.6.5/paperfmt-v6.6.5-setup.exe) | 41.3 MB | `F025051B3F709D9A` |  |
| 6.6.6 | [下载](https://github.com/DongMenWeiQian/paperfmt-download/releases/download/v6.6.6/paperfmt-v6.6.6-setup.exe) | 41.3 MB | `35915FB39998B76B` |  |
| 6.6.7 | [下载](https://github.com/DongMenWeiQian/paperfmt-download/releases/download/v6.6.7/paperfmt-v6.6.7-setup.exe) | 41.1 MB | `42F0FE35F5CEFA59` |  |
| 6.6.8 | [下载](https://github.com/DongMenWeiQian/paperfmt-download/releases/download/v6.6.8/paperfmt-v6.6.8-setup.exe) | 41.5 MB | `0C74DA8158A3D0F6` |  |
| 6.6.9 | [下载](https://github.com/DongMenWeiQian/paperfmt-download/releases/download/v6.6.9/paperfmt-v6.6.9-setup.exe) | 41.6 MB | `E2BDBA18C047167B` |  |
| 6.6.10 | [下载](https://github.com/DongMenWeiQian/paperfmt-download/releases/download/v6.6.10/paperfmt-v6.6.10-setup.exe) | 41.6 MB | `393C39689DF6A57D` |  |
| 6.6.11 | [下载](https://github.com/DongMenWeiQian/paperfmt-download/releases/download/v6.6.11/paperfmt-v6.6.11-setup.exe) | 41.6 MB | `384CC32BB7AC4BF4` |  |
| 6.6.12 | [下载](https://github.com/DongMenWeiQian/paperfmt-download/releases/download/v6.6.12/paperfmt-v6.6.12-setup.exe) | 41.6 MB | `7E79E669D2FEADC1` |  |
| 6.6.13 | [下载](https://github.com/DongMenWeiQian/paperfmt-download/releases/download/v6.6.13/paperfmt-v6.6.13-setup.exe) | 41.6 MB | `21A0BF0B8D3595C6` |  |
| 6.6.14 | [下载](https://github.com/DongMenWeiQian/paperfmt-download/releases/download/v6.6.14/paperfmt-v6.6.14-setup.exe) | 41.6 MB | `053755B1EEC725BA` |  |
| 6.6.15 | [下载](https://github.com/DongMenWeiQian/paperfmt-download/releases/download/v6.6.15/paperfmt-v6.6.15-setup.exe) | 41.6 MB | `EC2C162153D3C649` |  |
| 6.6.16 | [下载](https://github.com/DongMenWeiQian/paperfmt-download/releases/download/v6.6.16/paperfmt-v6.6.16-setup.exe) | 41.6 MB | `B9F5A2FAEE1207DE` |  |
| 6.6.17 | [下载](https://github.com/DongMenWeiQian/paperfmt-download/releases/download/v6.6.17/paperfmt-v6.6.17-setup.exe) | 41.6 MB | `A1E83F46CA5149F4` |  |
| 6.6.18 | [下载](https://github.com/DongMenWeiQian/paperfmt-download/releases/download/v6.6.18/paperfmt-v6.6.18-setup.exe) | 41.6 MB | `3E7A5568A27866A5` |  |
| 6.6.19 | [下载](https://github.com/DongMenWeiQian/paperfmt-download/releases/download/v6.6.19/paperfmt-v6.6.19-setup.exe) | 41.6 MB | `CF61B494F2B4857A` |  |
| 6.6.20 | [下载](https://github.com/DongMenWeiQian/paperfmt-download/releases/download/v6.6.20/paperfmt-v6.6.20-setup.exe) | 41.6 MB | `08C6A1A0F747CEAC` |  |
| 6.6.21 | [下载](https://github.com/DongMenWeiQian/paperfmt-download/releases/download/v6.6.21/paperfmt-v6.6.21-setup.exe) | 41.6 MB | `AFC72248727F17C9` | 历史版本 |
| 6.6.22 | [下载](https://github.com/DongMenWeiQian/paperfmt-download/releases/download/v6.6.22/paperfmt-v6.6.22-setup.exe) | 41.6 MB | `6839C8CF2DA5753A` |  |
| 6.6.24 | [下载](https://github.com/DongMenWeiQian/paperfmt-download/releases/download/v6.6.24/paperfmt-v6.6.24-setup.exe) | 41.7 MB | `2B4C4F0C75B29077` |  |
| 6.6.25 | [下载](https://github.com/DongMenWeiQian/paperfmt-download/releases/download/v6.6.25/paperfmt-v6.6.25-setup.exe) | 41.7 MB | `FC1D858CBDB06284` |  |
| 6.6.26 | [下载](https://github.com/DongMenWeiQian/paperfmt-download/releases/download/v6.6.26/paperfmt-v6.6.26-setup.exe) | 41.7 MB | `743EAC1F6B7184A8` |  |
| 6.6.27 | [下载](https://github.com/DongMenWeiQian/paperfmt-download/releases/download/v6.6.27/paperfmt-v6.6.27-setup.exe) | 41.7 MB | `D9693DD1ADD54D75` |  |
| 6.6.28 | [下载](https://github.com/DongMenWeiQian/paperfmt-download/releases/download/v6.6.28/paperfmt-v6.6.28-setup.exe) | 41.7 MB | `0A1F7639D47246F8` |  |
| 6.6.29 | [下载](https://github.com/DongMenWeiQian/paperfmt-download/releases/download/v6.6.29/paperfmt-v6.6.29-setup.exe) | 41.7 MB | `4E2A3090537F06A6` |  |
| 6.6.31 | [下载](https://github.com/DongMenWeiQian/paperfmt-download/releases/download/v6.6.31/paperfmt-v6.6.31-setup.exe) | 46.2 MB | `2706D0E00255DB71` |  |
| 6.6.32 | [下载](https://github.com/DongMenWeiQian/paperfmt-download/releases/download/v6.6.32/paperfmt-v6.6.32-setup.exe) | 46.2 MB | `6B52332813CA010A` |  |
| 6.6.33 | [下载](https://github.com/DongMenWeiQian/paperfmt-download/releases/download/v6.6.33/paperfmt-v6.6.33-setup.exe) | 46.2 MB | `23F6DE421882A194` |  |
| 6.6.34 | [下载](https://github.com/DongMenWeiQian/paperfmt-download/releases/download/v6.6.34/paperfmt-v6.6.34-setup.exe) | 46.2 MB | `C2503D3A97B59BFC` |  |
| 7.0.0 | [下载](https://github.com/DongMenWeiQian/paperfmt-download/releases/download/v7.0.0/paperfmt-v7.0.0-setup.exe) | 46.3 MB | `E6C608E99875877A` |  |
| 7.0.1 | [下载](https://github.com/DongMenWeiQian/paperfmt-download/releases/download/v7.0.1/paperfmt-v7.0.1-setup.exe) | 46.3 MB | `2560E654469C86EC` |  |
| 7.0.2 | [下载](https://github.com/DongMenWeiQian/paperfmt-download/releases/download/v7.0.2/paperfmt-v7.0.2-setup.exe) | 46.3 MB | `300763F3266D8E70` |  |
| 7.0.3 | [下载](https://github.com/DongMenWeiQian/paperfmt-download/releases/download/v7.0.3/paperfmt-v7.0.3-setup.exe) | 46.3 MB | `404E98B5B2765889` |  |
| 7.0.4 | [下载](https://github.com/DongMenWeiQian/paperfmt-download/releases/download/v7.0.4/paperfmt-v7.0.4-setup.exe) | 46.3 MB | `235FCC4BF095C3B6` |  |
| 7.1.0 | [下载](https://github.com/DongMenWeiQian/paperfmt-download/releases/download/v7.1.0/paperfmt-v7.1.0-setup.exe) | 46.3 MB | `BAD4468FA5A89E3C` |  |
| 7.2.0 | [下载](https://github.com/DongMenWeiQian/paperfmt-download/releases/download/v7.2.0/paperfmt-v7.2.0-setup.exe) | 46.3 MB | `CCD8262564122104` |  |
| 7.3.0 | [下载](https://github.com/DongMenWeiQian/paperfmt-download/releases/download/v7.3.0/paperfmt-v7.3.0-setup.exe) | 46.3 MB | `9E4456348A576D48` |  |
| 7.3.1 | [下载](https://github.com/DongMenWeiQian/paperfmt-download/releases/download/v7.3.1/paperfmt-v7.3.1-setup.exe) | 46.3 MB | `38386B4E177C66B3` |  |
| 7.4.0 | [下载](https://github.com/DongMenWeiQian/paperfmt-download/releases/download/v7.4.0/paperfmt-v7.4.0-setup.exe) | 46.3 MB | `AFB0423961922B54` |  |
| 7.5.0 | [下载](https://github.com/DongMenWeiQian/paperfmt-download/releases/download/v7.5.0/paperfmt-v7.5.0-setup.exe) | 46.3 MB | `869A0C59C4B25D12` |  |
| 7.5.1 | [下载](https://github.com/DongMenWeiQian/paperfmt-download/releases/download/v7.5.1/paperfmt-v7.5.1-setup.exe) | 46.3 MB | `44D9F5495ED4779B` |  |
| 7.5.2 | [下载](https://github.com/DongMenWeiQian/paperfmt-download/releases/download/v7.5.2/paperfmt-v7.5.2-setup.exe) | 46.3 MB | `604637A4644CA961` |  |
| 7.5.3 | [下载](https://github.com/DongMenWeiQian/paperfmt-download/releases/download/v7.5.3/paperfmt-v7.5.3-setup.exe) | 46.3 MB | `74B2F5F463923B29` |  |
| 7.5.4 | [下载](https://github.com/DongMenWeiQian/paperfmt-download/releases/download/v7.5.4/paperfmt-v7.5.4-setup.exe) | 46.3 MB | `293D73072DDF82EB` |  |
| 7.5.5 | [下载](https://github.com/DongMenWeiQian/paperfmt-download/releases/download/v7.5.5/paperfmt-v7.5.5-setup.exe) | 46.3 MB | `DA0A22E11A9864D8` |  |
| 7.6.0 | [下载](https://github.com/DongMenWeiQian/paperfmt-download/releases/download/v7.6.0/paperfmt-v7.6.0-setup.exe) | 46.3 MB | `F41BA63C0626BF5F` |  |
| 7.7.0 | [下载](https://github.com/DongMenWeiQian/paperfmt-download/releases/download/v7.7.0/paperfmt-v7.7.0-setup.exe) | 46.3 MB | `5E290AE9D8C0D795` |  |
| 7.7.1 | [下载](https://github.com/DongMenWeiQian/paperfmt-download/releases/download/v7.7.1/paperfmt-v7.7.1-setup.exe) | 46.3 MB | `34A55D9DCFB7FEE8` |  |
| 7.7.2 | [下载](https://github.com/DongMenWeiQian/paperfmt-download/releases/download/v7.7.2/paperfmt-v7.7.2-setup.exe) | 46.3 MB | `66050B80FA8335FF` |  |
| 7.7.4 | [下载](https://github.com/DongMenWeiQian/paperfmt-download/releases/download/v7.7.4/paperfmt-v7.7.4-setup.exe) | 46.3 MB | `BF2AC26EB760D781` |  |
| 7.7.5 | [下载](https://github.com/DongMenWeiQian/paperfmt-download/releases/download/v7.7.5/paperfmt-v7.7.5-setup.exe) | 46.3 MB | `3065788524B7875E` |  |
| 7.7.6 | [下载](https://github.com/DongMenWeiQian/paperfmt-download/releases/download/v7.7.6/paperfmt-v7.7.6-setup.exe) | 46.3 MB | `0651741FA3FDC0E7` |  |
| 7.7.7 | [下载](https://github.com/DongMenWeiQian/paperfmt-download/releases/download/v7.7.7/paperfmt-v7.7.7-setup.exe) | 46.4 MB | `7732A5E7988B5270` |  |
| 7.7.8 | [下载](https://github.com/DongMenWeiQian/paperfmt-download/releases/download/v7.7.8/paperfmt-v7.7.8-setup.exe) | 46.3 MB | `104D5BE5E6E7A182` |  |
| 7.7.9 | [下载](https://github.com/DongMenWeiQian/paperfmt-download/releases/download/v7.7.9/paperfmt-v7.7.9-setup.exe) | 46.3 MB | `26B80345941AE3B1` |  |
| 7.7.10 | [下载](https://github.com/DongMenWeiQian/paperfmt-download/releases/download/v7.7.10/paperfmt-v7.7.10-setup.exe) | 46.3 MB | `5BD7BE5795518B56` |  |
| 7.7.12 | [下载](https://github.com/DongMenWeiQian/paperfmt-download/releases/download/v7.7.12/paperfmt-v7.7.12-setup.exe) | 46.3 MB | `5520752624220BBA` |  |
| 7.7.13 | [下载](https://github.com/DongMenWeiQian/paperfmt-download/releases/download/v7.7.13/paperfmt-v7.7.13-setup.exe) | 46.3 MB | `C51751F55CAEC417` |  |
| 7.7.14 | [下载](https://github.com/DongMenWeiQian/paperfmt-download/releases/download/v7.7.14/paperfmt-v7.7.14-setup.exe) | 46.4 MB | `D773687787BBAAEC` |  |
| 7.7.15 | [下载](https://github.com/DongMenWeiQian/paperfmt-download/releases/download/v7.7.15/paperfmt-v7.7.15-setup.exe) | 46.3 MB | `8A98BCC526D8F960` |  |
| 7.7.16 | [下载](https://github.com/DongMenWeiQian/paperfmt-download/releases/download/v7.7.16/paperfmt-v7.7.16-setup.exe) | 46.4 MB | `C6DC11F8DD48D9DC` |  |
| 7.7.17 | [下载](https://github.com/DongMenWeiQian/paperfmt-download/releases/download/v7.7.17/paperfmt-v7.7.17-setup.exe) | 46.4 MB | `8678CD5F55F3F601` |  |
