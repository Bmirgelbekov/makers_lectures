# Список asr моделей на серверах

**eg_vodafone**
[eg_asr]
10.20.0.5
IMAGE: cr.cyberdev.app/asr_quartznet_chpt_20_vodafone_medicalensurance_synthetic_eg_v1 (musing_poitras) 
CONTAINER ID: 6acb1f992f70


**kazteleoport_kz**
[asr_servers]
10.1.0.11 ansible_hostname=kz-cyber-kzport-asr-01
IMAGE: cr.cyber-net.ai/asr_kz_ru:latest (asr_kz_ru)
CONTAINER ID: 1bc95d1c0b54

10.1.0.12 ansible_hostname=kz-cyber-kzport-asr-02
IMAGE: cr.cyber-net.ai/asr_kz_ru:latest (asr_kz_ru)
CONTAINER ID: 07d7980a4342

10.1.0.13 ansible_hostname=kz-cyber-kzport-asr-03
IMAGE: cr.cyber-net.ai/asr_kz_ru:latest (asr_kz_ru)
CONTAINER ID: 8690a841d754

10.1.0.14 ansible_hostname=kz-cyber-kzport-asr-04
IMAGE: cr.cyber-net.ai/asr_kz_ru:latest (asr_kz_ru)
CONTAINER ID: a9da16bebda6

10.1.0.15 ansible_hostname=kz-cyber-kzport-asr-05
IMAGE: cr.cyber-net.ai/asr_kz_ru:latest (asr_kz_ru)
CONTAINER ID: c26c1f2da81c

10.1.0.16 ansible_hostname=kz-cyber-kzport-asr-06
IMAGE: cr.cyber-net.ai/asr_kz_ru:latest (asr_kz_ru)
CONTAINER ID: bd909b89a4b2

10.1.0.17 ansible_hostname=kz-cyber-kzport-asr-07
IMAGE: cr.cyberdev.app/transduce_hcb_aster_kcell_kzru_v2_03_10_2024 (cool_moser)
CONTAINER ID: a0120c15bfbf

10.1.0.18 ansible_hostname=kz-cyber-kzport-asr-08
IMAGE: cr.cyberdev.app/transduce_hcb_aster_kcell_kzru_v2_03_10_2024 (sweet_jennings)
CONTAINER ID: 0e7cabb9a7c3

10.1.0.19 ansible_hostname=kz-cyber-kzport-asr-09
IMAGE: cr.cyberdev.app/hcb_tm_02_09_2024:latest (wonderful_rhodes)
CONTAINER ID: a0f791a80d62

IMAGE: cr.cyberdev.app/quartz_numbers_8aux2024 (optimistic_curie)
CONTAINER ID: 201301cc3348


[aster_quarz_asr]
10.1.0.21 ansible_hostname=kz-cyber-kzport-asr-11
IMAGE: cr.cyberdev.app/transduce_hcb_aster_kcell_kzru_v2_03_10_2024 (clever_carson)
CONTAINER ID: 5ea54a302542


[quartznet_egypt]
10.1.0.25 ansible_hostname=kz-cyber-kzport-kg-quartznet-02
IMAGE: cr.cyberdev.app/transduce_hcb_aster_kcell_kzru_v2_03_10_2024 (mystifying_lovelace)
CONTAINER ID: 22dcf01b42e1


[quartznet_servers]
10.1.0.20 ansible_hostname=kz-cyber-kzport-asr-10
IMAGE: cr.cyber-net.ai/quartznet_garantia:latest (nervous_cohen)
CONTAINER ID: 2c16a61eed85


[kg_ru_asr_servers]
10.1.0.22 ansible_hostname=kz-cyber-kzport-asr-12 *не удалось подключится*
10.1.0.23 ansible_hostname=kz-cyber-kzport-asr-13 *не удалось подключится*


**kg_datatime**
[kg_asr]
10.10.0.10 ansible_hostname=kg-asr-01
IMAGE: cr.cyber-net.ai/asr_kg_ru (cool_buck)
CONTAINER ID: 78d1aaaab5ac

10.10.0.11 ansible_hostname=kg-asr-02
IMAGE: cr.cyberdev.app/quartznet_beeline_kg_jun_6_2024_3_8 (beautiful_lumiere)
CONTAINER ID: 55cefcd97a73

10.10.0.232 ansible_hostname=kg-prod-asr03-cyber
IMAGE: cr.cyberdev.app/asr_kg_ru (awesome_bell)
CONTAINER ID: 02a2627a34db


**lincore_inventory**
[prod_asr_new_cluster]
85.198.89.6  ansible_hostname=kz-prod-asr50-cyber *не удалось подключится*
85.198.89.61 ansible_hostname=kz-prod-asr51-cyber *не удалось подключится*


**us_lincore_nj**
[usa_asr]
10.30.0.6 ansible_hostname=usa-asr
IMAGE: cr.cyberdev.app/en_stt_demo_usa (sweet_chaplygin)
CONTAINER ID: ace56d93d5f5


**uzbekistan_inventory**
[us_asr_servers]
176.96.241.81 ansible_hostname=uz-prod-asr03-cyber
IMAGE: cr.cyber-net.ai/asr_uzru_ruiin:10.3 (inspiring_raman)
CONTAINER ID: 6cb501a327e1

176.96.241.82 ansible_hostname=uz-prod-asr04-cyber
IMAGE: cr.cyber-net.ai/asr_uzru_ruiin:10.3 (xenodochial_hodgkin)
CONTAINER ID: 0ea1dee080ed

176.96.241.83 ansible_hostname=uz-prod-asr05-cyber
IMAGE: cr.cyber-net.ai/asr_uzru_ruiin:10.3 (sweet_bassi)
CONTAINER ID: ba91a48fb86d

176.96.241.84 ansible_hostname=uz-prod-asr06-cyber
IMAGE: cr.cyber-net.ai/asr_uzru_ruiin:10.3 (nice_euler)
CONTAINER ID: 6259e83c92cf

176.221.28.67 ansible_hostname=uz-prod-asr08-cyber
IMAGE: cr.cyber-net.ai/asr_uzru_ruiin:10.3 (sad_kare)
CONTAINER ID: 458c7d6019bc


[uz_new_asr]
10.41.0.16 ansible_hostname=uz-prod-asr12-cyber
IMAGE: cr.cyberdev.app/asr_transducer_hat_ckpt_10_universal_uzru_v2_12112024:latest (universal_uz_ru)
CONTAINER ID: 6dd6d00c5b04

10.41.0.17 ansible_hostname=uz-prod-asr13-cyber
IMAGE: cr.cyberdev.app/asr_transducer_hat_ckpt_10_universal_uzru_v2_12112024:latest (universal_uz_ru)
CONTAINER ID: 75fb259d4b8a

10.41.0.18 ansible_hostname=uz-prod-asr14-cyber
IMAGE: cr.cyberdev.app/asr_transducer_hat_ckpt_10_universal_uzru_v2_12112024:latest (universal_uz_ru)
CONTAINER ID: 78858908be2a

10.41.0.19 ansible_hostname=uz-prod-asr15-cyber
IMAGE: cr.cyberdev.app/asr_transducer_hat_ckpt_10_universal_uzru_v2_12112024:latest (universal_uz_ru)
CONTAINER ID: 800101bb65b1

10.41.0.20 ansible_hostname=uz-prod-asr16-cyber
IMAGE: cr.cyberdev.app/asr_transducer_hat_ckpt_10_universal_uzru_v2_12112024:latest (universal_uz_ru)
CONTAINER ID: e195f24980c2

10.41.0.28 ansible_hostname=uz-prod-asr17-cyber
IMAGE: cr.cyberdev.app/asr_transducer_hat_ckpt_10_universal_uzru_v2_12112024:latest (universal_uz_ru)
CONTAINER ID: 22d7cc191fce


**vk_cloud**
[vk_cloud_asr_servers]
93.183.84.105 ansible_hostname=vk-asr-test-1-1 *не удалось подключится*
93.183.84.106 ansible_hostname=vk-asr-test-1-2 *не удалось подключится*














