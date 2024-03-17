<script setup>
import { ref } from "vue"
import HomeModuleTitle from "@/components/Home/HomeModuleTitle.vue"
// 定义一个内容数组
const contentList = ref(
    [
        {
            title: "精品栏目",
            optionList: [
                {
                    value: "最新",
                    content: [
                        {
                            img: "https://shp.qpic.cn/cfwebcap/0/d28f038214234eaa82459c18ad7a9e77/0/?width=230&height=140",
                            title: "峡谷大气层 | 你知道赵云出了血魔之怒意味着什么吗？",
                            watch: 2970,
                        },
                        {
                            img: "https://shp.qpic.cn/cfwebcap/0/d28f038214234eaa82459c18ad7a9e77/0/?width=230&height=140",
                            title: "峡谷大气层 | 你知道赵云出了血魔之怒意味着什么吗？",
                            watch: 2970,
                        },
                        {
                            img: "https://shp.qpic.cn/cfwebcap/0/d28f038214234eaa82459c18ad7a9e77/0/?width=230&height=140",
                            title: "峡谷大气层 | 你知道赵云出了血魔之怒意味着什么吗？",
                            watch: 2970,
                        },
                        {
                            img: "https://shp.qpic.cn/cfwebcap/0/d28f038214234eaa82459c18ad7a9e77/0/?width=230&height=140",
                            title: "峡谷大气层 | 你知道赵云出了血魔之怒意味着什么吗？",
                            watch: 2970,
                        },
                        {
                            img: "https://shp.qpic.cn/cfwebcap/0/d28f038214234eaa82459c18ad7a9e77/0/?width=230&height=140",
                            title: "峡谷大气层 | 你知道赵云出了血魔之怒意味着什么吗？",
                            watch: 2970,
                        },
                        {
                            img: "https://shp.qpic.cn/cfwebcap/0/d28f038214234eaa82459c18ad7a9e77/0/?width=230&height=140",
                            title: "峡谷大气层 | 你知道赵云出了血魔之怒意味着什么吗？",
                            watch: 2970,
                        },
                        {
                            img: "https://shp.qpic.cn/cfwebcap/0/d28f038214234eaa82459c18ad7a9e77/0/?width=230&height=140",
                            title: "峡谷大气层 | 你知道赵云出了血魔之怒意味着什么吗？",
                            watch: 2970,
                        },
                        {
                            img: "https://shp.qpic.cn/cfwebcap/0/d28f038214234eaa82459c18ad7a9e77/0/?width=230&height=140",
                            title: "峡谷大气层 | 你知道赵云出了血魔之怒意味着什么吗？",
                            watch: 2970,
                        }
                    ]
                },
                {
                    value: "峡谷大气层",
                    content: [
                        {
                            img: "https://shp.qpic.cn/cfwebcap/0/e69f0aad66a564e8242e3711afa017c5/0/?width=230&height=140",
                            title: "峡谷大气层 | 你知道赵云出了血魔之怒意味着什么吗？",
                            watch: 2970,
                        },
                        {
                            img: "https://shp.qpic.cn/cfwebcap/0/e69f0aad66a564e8242e3711afa017c5/0/?width=230&height=140",
                            title: "峡谷大气层 | 你知道赵云出了血魔之怒意味着什么吗？",
                            watch: 2970,
                        },
                        {
                            img: "https://shp.qpic.cn/cfwebcap/0/e69f0aad66a564e8242e3711afa017c5/0/?width=230&height=140",
                            title: "峡谷大气层 | 你知道赵云出了血魔之怒意味着什么吗？",
                            watch: 2970,
                        },
                        {
                            img: "https://shp.qpic.cn/cfwebcap/0/e69f0aad66a564e8242e3711afa017c5/0/?width=230&height=140",
                            title: "峡谷大气层 | 你知道赵云出了血魔之怒意味着什么吗？",
                            watch: 2970,
                        },
                        {
                            img: "https://shp.qpic.cn/cfwebcap/0/e69f0aad66a564e8242e3711afa017c5/0/?width=230&height=140",
                            title: "峡谷大气层 | 你知道赵云出了血魔之怒意味着什么吗？",
                            watch: 2970,
                        },
                        {
                            img: "https://shp.qpic.cn/cfwebcap/0/e69f0aad66a564e8242e3711afa017c5/0/?width=230&height=140",
                            title: "峡谷大气层 | 你知道赵云出了血魔之怒意味着什么吗？",
                            watch: 2970,
                        },
                        {
                            img: "https://shp.qpic.cn/cfwebcap/0/e69f0aad66a564e8242e3711afa017c5/0/?width=230&height=140",
                            title: "峡谷大气层 | 你知道赵云出了血魔之怒意味着什么吗？",
                            watch: 2970,
                        },
                        {
                            img: "https://shp.qpic.cn/cfwebcap/0/e69f0aad66a564e8242e3711afa017c5/0/?width=230&height=140",
                            title: "峡谷大气层 | 你知道赵云出了血魔之怒意味着什么吗？",
                            watch: 2970,
                        },
                    ]
                },
                {
                    value: "马菠萝奇闻录",
                    content: [
                        {
                            img: "https://shp.qpic.cn/cfwebcap/0/f5fa39040a51d05bdd7587afdc1b5ebc/0/?width=230&height=140",
                            title: "【马菠萝奇闻录】第47期：我也不想出形昭啊，可他是老六诶！",
                            watch: 2970,
                        },
                        {
                            img: "https://shp.qpic.cn/cfwebcap/0/f5fa39040a51d05bdd7587afdc1b5ebc/0/?width=230&height=140",
                            title: "【马菠萝奇闻录】第47期：我也不想出形昭啊，可他是老六诶！",
                            watch: 2970,
                        },
                        {
                            img: "https://shp.qpic.cn/cfwebcap/0/f5fa39040a51d05bdd7587afdc1b5ebc/0/?width=230&height=140",
                            title: "【马菠萝奇闻录】第47期：我也不想出形昭啊，可他是老六诶！",
                            watch: 2970,
                        },
                        {
                            img: "https://shp.qpic.cn/cfwebcap/0/f5fa39040a51d05bdd7587afdc1b5ebc/0/?width=230&height=140",
                            title: "【马菠萝奇闻录】第47期：我也不想出形昭啊，可他是老六诶！",
                            watch: 2970,
                        },
                        {
                            img: "https://shp.qpic.cn/cfwebcap/0/f5fa39040a51d05bdd7587afdc1b5ebc/0/?width=230&height=140",
                            title: "【马菠萝奇闻录】第47期：我也不想出形昭啊，可他是老六诶！",
                            watch: 2970,
                        },
                        {
                            img: "https://shp.qpic.cn/cfwebcap/0/f5fa39040a51d05bdd7587afdc1b5ebc/0/?width=230&height=140",
                            title: "【马菠萝奇闻录】第47期：我也不想出形昭啊，可他是老六诶！",
                            watch: 2970,
                        },
                        {
                            img: "https://shp.qpic.cn/cfwebcap/0/f5fa39040a51d05bdd7587afdc1b5ebc/0/?width=230&height=140",
                            title: "【马菠萝奇闻录】第47期：我也不想出形昭啊，可他是老六诶！",
                            watch: 2970,
                        },
                        {
                            img: "https://shp.qpic.cn/cfwebcap/0/f5fa39040a51d05bdd7587afdc1b5ebc/0/?width=230&height=140",
                            title: "【马菠萝奇闻录】第47期：我也不想出形昭啊，可他是老六诶！",
                            watch: 2970,
                        },
                    ]
                },
                {
                    value: "狄仁杰封神榜",
                    content: [
                        {
                            img: "https://shp.qpic.cn/cfwebcap/0/298b55b64b149999f5884b92b2c9e884/0/?width=230&height=140",
                            title: "【狄仁杰封神榜】第89期 锁定透视 守护峡谷草丛！",
                            watch: 6786
                        },
                        {
                            img: "https://shp.qpic.cn/cfwebcap/0/298b55b64b149999f5884b92b2c9e884/0/?width=230&height=140",
                            title: "【狄仁杰封神榜】第89期 锁定透视 守护峡谷草丛！",
                            watch: 6786
                        },
                        {
                            img: "https://shp.qpic.cn/cfwebcap/0/298b55b64b149999f5884b92b2c9e884/0/?width=230&height=140",
                            title: "【狄仁杰封神榜】第89期 锁定透视 守护峡谷草丛！",
                            watch: 6786
                        },
                        {
                            img: "https://shp.qpic.cn/cfwebcap/0/298b55b64b149999f5884b92b2c9e884/0/?width=230&height=140",
                            title: "【狄仁杰封神榜】第89期 锁定透视 守护峡谷草丛！",
                            watch: 6786
                        },
                        {
                            img: "https://shp.qpic.cn/cfwebcap/0/298b55b64b149999f5884b92b2c9e884/0/?width=230&height=140",
                            title: "【狄仁杰封神榜】第89期 锁定透视 守护峡谷草丛！",
                            watch: 6786
                        },
                        {
                            img: "https://shp.qpic.cn/cfwebcap/0/298b55b64b149999f5884b92b2c9e884/0/?width=230&height=140",
                            title: "【狄仁杰封神榜】第89期 锁定透视 守护峡谷草丛！",
                            watch: 6786
                        },
                        {
                            img: "https://shp.qpic.cn/cfwebcap/0/298b55b64b149999f5884b92b2c9e884/0/?width=230&height=140",
                            title: "【狄仁杰封神榜】第89期 锁定透视 守护峡谷草丛！",
                            watch: 6786
                        },
                        {
                            img: "https://shp.qpic.cn/cfwebcap/0/298b55b64b149999f5884b92b2c9e884/0/?width=230&height=140",
                            title: "【狄仁杰封神榜】第89期 锁定透视 守护峡谷草丛！",
                            watch: 6786
                        },
                    ]
                },
                {
                    value: "游走基本法",
                    content: [
                        {
                            img: "https://shp.qpic.cn/cfwebcap/0/d28f038214234eaa82459c18ad7a9e77/0/?width=230&height=140",
                            title: "峡谷大气层 | 你知道赵云出了血魔之怒意味着什么吗？",
                            watch: 2970,
                        },
                        {
                            img: "https://shp.qpic.cn/cfwebcap/0/d28f038214234eaa82459c18ad7a9e77/0/?width=230&height=140",
                            title: "峡谷大气层 | 你知道赵云出了血魔之怒意味着什么吗？",
                            watch: 2970,
                        },
                        {
                            img: "https://shp.qpic.cn/cfwebcap/0/d28f038214234eaa82459c18ad7a9e77/0/?width=230&height=140",
                            title: "峡谷大气层 | 你知道赵云出了血魔之怒意味着什么吗？",
                            watch: 2970,
                        },
                        {
                            img: "https://shp.qpic.cn/cfwebcap/0/d28f038214234eaa82459c18ad7a9e77/0/?width=230&height=140",
                            title: "峡谷大气层 | 你知道赵云出了血魔之怒意味着什么吗？",
                            watch: 2970,
                        },
                        {
                            img: "https://shp.qpic.cn/cfwebcap/0/d28f038214234eaa82459c18ad7a9e77/0/?width=230&height=140",
                            title: "峡谷大气层 | 你知道赵云出了血魔之怒意味着什么吗？",
                            watch: 2970,
                        },
                        {
                            img: "https://shp.qpic.cn/cfwebcap/0/d28f038214234eaa82459c18ad7a9e77/0/?width=230&height=140",
                            title: "峡谷大气层 | 你知道赵云出了血魔之怒意味着什么吗？",
                            watch: 2970,
                        },
                        {
                            img: "https://shp.qpic.cn/cfwebcap/0/d28f038214234eaa82459c18ad7a9e77/0/?width=230&height=140",
                            title: "峡谷大气层 | 你知道赵云出了血魔之怒意味着什么吗？",
                            watch: 2970,
                        },
                        {
                            img: "https://shp.qpic.cn/cfwebcap/0/d28f038214234eaa82459c18ad7a9e77/0/?width=230&height=140",
                            title: "峡谷大气层 | 你知道赵云出了血魔之怒意味着什么吗？",
                            watch: 2970,
                        }
                    ]
                },
                {
                    value: "野王修炼手册",

                    content: [
                        {
                            img: "https://shp.qpic.cn/cfwebcap/0/e69f0aad66a564e8242e3711afa017c5/0/?width=230&height=140",
                            title: "峡谷大气层 | 你知道赵云出了血魔之怒意味着什么吗？",
                            watch: 2970,
                        },
                        {
                            img: "https://shp.qpic.cn/cfwebcap/0/e69f0aad66a564e8242e3711afa017c5/0/?width=230&height=140",
                            title: "峡谷大气层 | 你知道赵云出了血魔之怒意味着什么吗？",
                            watch: 2970,
                        },
                        {
                            img: "https://shp.qpic.cn/cfwebcap/0/e69f0aad66a564e8242e3711afa017c5/0/?width=230&height=140",
                            title: "峡谷大气层 | 你知道赵云出了血魔之怒意味着什么吗？",
                            watch: 2970,
                        },
                        {
                            img: "https://shp.qpic.cn/cfwebcap/0/e69f0aad66a564e8242e3711afa017c5/0/?width=230&height=140",
                            title: "峡谷大气层 | 你知道赵云出了血魔之怒意味着什么吗？",
                            watch: 2970,
                        },
                        {
                            img: "https://shp.qpic.cn/cfwebcap/0/e69f0aad66a564e8242e3711afa017c5/0/?width=230&height=140",
                            title: "峡谷大气层 | 你知道赵云出了血魔之怒意味着什么吗？",
                            watch: 2970,
                        },
                        {
                            img: "https://shp.qpic.cn/cfwebcap/0/e69f0aad66a564e8242e3711afa017c5/0/?width=230&height=140",
                            title: "峡谷大气层 | 你知道赵云出了血魔之怒意味着什么吗？",
                            watch: 2970,
                        },
                        {
                            img: "https://shp.qpic.cn/cfwebcap/0/e69f0aad66a564e8242e3711afa017c5/0/?width=230&height=140",
                            title: "峡谷大气层 | 你知道赵云出了血魔之怒意味着什么吗？",
                            watch: 2970,
                        },
                        {
                            img: "https://shp.qpic.cn/cfwebcap/0/e69f0aad66a564e8242e3711afa017c5/0/?width=230&height=140",
                            title: "峡谷大气层 | 你知道赵云出了血魔之怒意味着什么吗？",
                            watch: 2970,
                        },
                    ]
                },
                {
                    value: "法王的荣耀",
                    content: [
                        {
                            img: "https://shp.qpic.cn/cfwebcap/0/f5fa39040a51d05bdd7587afdc1b5ebc/0/?width=230&height=140",
                            title: "【马菠萝奇闻录】第47期：我也不想出形昭啊，可他是老六诶！",
                            watch: 2970,
                        },
                        {
                            img: "https://shp.qpic.cn/cfwebcap/0/f5fa39040a51d05bdd7587afdc1b5ebc/0/?width=230&height=140",
                            title: "【马菠萝奇闻录】第47期：我也不想出形昭啊，可他是老六诶！",
                            watch: 2970,
                        },
                        {
                            img: "https://shp.qpic.cn/cfwebcap/0/f5fa39040a51d05bdd7587afdc1b5ebc/0/?width=230&height=140",
                            title: "【马菠萝奇闻录】第47期：我也不想出形昭啊，可他是老六诶！",
                            watch: 2970,
                        },
                        {
                            img: "https://shp.qpic.cn/cfwebcap/0/f5fa39040a51d05bdd7587afdc1b5ebc/0/?width=230&height=140",
                            title: "【马菠萝奇闻录】第47期：我也不想出形昭啊，可他是老六诶！",
                            watch: 2970,
                        },
                        {
                            img: "https://shp.qpic.cn/cfwebcap/0/f5fa39040a51d05bdd7587afdc1b5ebc/0/?width=230&height=140",
                            title: "【马菠萝奇闻录】第47期：我也不想出形昭啊，可他是老六诶！",
                            watch: 2970,
                        },
                        {
                            img: "https://shp.qpic.cn/cfwebcap/0/f5fa39040a51d05bdd7587afdc1b5ebc/0/?width=230&height=140",
                            title: "【马菠萝奇闻录】第47期：我也不想出形昭啊，可他是老六诶！",
                            watch: 2970,
                        },
                        {
                            img: "https://shp.qpic.cn/cfwebcap/0/f5fa39040a51d05bdd7587afdc1b5ebc/0/?width=230&height=140",
                            title: "【马菠萝奇闻录】第47期：我也不想出形昭啊，可他是老六诶！",
                            watch: 2970,
                        },
                        {
                            img: "https://shp.qpic.cn/cfwebcap/0/f5fa39040a51d05bdd7587afdc1b5ebc/0/?width=230&height=140",
                            title: "【马菠萝奇闻录】第47期：我也不想出形昭啊，可他是老六诶！",
                            watch: 2970,
                        },
                    ]
                },
            ]
        },
        {
            title: "赛事精品",
            optionList: [
                {
                    value: "王者炸麦了",
                    content: [
                        {
                            img: "https://shp.qpic.cn/cfwebcap/0/d28f038214234eaa82459c18ad7a9e77/0/?width=230&height=140",
                            title: "峡谷大气层 | 你知道赵云出了血魔之怒意味着什么吗？",
                            watch: 2970,
                        },
                        {
                            img: "https://shp.qpic.cn/cfwebcap/0/d28f038214234eaa82459c18ad7a9e77/0/?width=230&height=140",
                            title: "峡谷大气层 | 你知道赵云出了血魔之怒意味着什么吗？",
                            watch: 2970,
                        },
                        {
                            img: "https://shp.qpic.cn/cfwebcap/0/d28f038214234eaa82459c18ad7a9e77/0/?width=230&height=140",
                            title: "峡谷大气层 | 你知道赵云出了血魔之怒意味着什么吗？",
                            watch: 2970,
                        },
                        {
                            img: "https://shp.qpic.cn/cfwebcap/0/d28f038214234eaa82459c18ad7a9e77/0/?width=230&height=140",
                            title: "峡谷大气层 | 你知道赵云出了血魔之怒意味着什么吗？",
                            watch: 2970,
                        },
                        {
                            img: "https://shp.qpic.cn/cfwebcap/0/d28f038214234eaa82459c18ad7a9e77/0/?width=230&height=140",
                            title: "峡谷大气层 | 你知道赵云出了血魔之怒意味着什么吗？",
                            watch: 2970,
                        },
                        {
                            img: "https://shp.qpic.cn/cfwebcap/0/d28f038214234eaa82459c18ad7a9e77/0/?width=230&height=140",
                            title: "峡谷大气层 | 你知道赵云出了血魔之怒意味着什么吗？",
                            watch: 2970,
                        },
                        {
                            img: "https://shp.qpic.cn/cfwebcap/0/d28f038214234eaa82459c18ad7a9e77/0/?width=230&height=140",
                            title: "峡谷大气层 | 你知道赵云出了血魔之怒意味着什么吗？",
                            watch: 2970,
                        },
                        {
                            img: "https://shp.qpic.cn/cfwebcap/0/d28f038214234eaa82459c18ad7a9e77/0/?width=230&height=140",
                            title: "峡谷大气层 | 你知道赵云出了血魔之怒意味着什么吗？",
                            watch: 2970,
                        }
                    ]
                },
                {
                    value: "荣耀大话王",
                    content: [
                        {
                            img: "https://shp.qpic.cn/cfwebcap/0/e69f0aad66a564e8242e3711afa017c5/0/?width=230&height=140",
                            title: "峡谷大气层 | 你知道赵云出了血魔之怒意味着什么吗？",
                            watch: 2970,
                        },
                        {
                            img: "https://shp.qpic.cn/cfwebcap/0/e69f0aad66a564e8242e3711afa017c5/0/?width=230&height=140",
                            title: "峡谷大气层 | 你知道赵云出了血魔之怒意味着什么吗？",
                            watch: 2970,
                        },
                        {
                            img: "https://shp.qpic.cn/cfwebcap/0/e69f0aad66a564e8242e3711afa017c5/0/?width=230&height=140",
                            title: "峡谷大气层 | 你知道赵云出了血魔之怒意味着什么吗？",
                            watch: 2970,
                        },
                        {
                            img: "https://shp.qpic.cn/cfwebcap/0/e69f0aad66a564e8242e3711afa017c5/0/?width=230&height=140",
                            title: "峡谷大气层 | 你知道赵云出了血魔之怒意味着什么吗？",
                            watch: 2970,
                        },
                        {
                            img: "https://shp.qpic.cn/cfwebcap/0/e69f0aad66a564e8242e3711afa017c5/0/?width=230&height=140",
                            title: "峡谷大气层 | 你知道赵云出了血魔之怒意味着什么吗？",
                            watch: 2970,
                        },
                        {
                            img: "https://shp.qpic.cn/cfwebcap/0/e69f0aad66a564e8242e3711afa017c5/0/?width=230&height=140",
                            title: "峡谷大气层 | 你知道赵云出了血魔之怒意味着什么吗？",
                            watch: 2970,
                        },
                        {
                            img: "https://shp.qpic.cn/cfwebcap/0/e69f0aad66a564e8242e3711afa017c5/0/?width=230&height=140",
                            title: "峡谷大气层 | 你知道赵云出了血魔之怒意味着什么吗？",
                            watch: 2970,
                        },
                        {
                            img: "https://shp.qpic.cn/cfwebcap/0/e69f0aad66a564e8242e3711afa017c5/0/?width=230&height=140",
                            title: "峡谷大气层 | 你知道赵云出了血魔之怒意味着什么吗？",
                            watch: 2970,
                        },
                    ]
                },
                {
                    value: "KPL云电台",
                    content: [
                        {
                            img: "https://shp.qpic.cn/cfwebcap/0/f5fa39040a51d05bdd7587afdc1b5ebc/0/?width=230&height=140",
                            title: "【马菠萝奇闻录】第47期：我也不想出形昭啊，可他是老六诶！",
                            watch: 2970,
                        },
                        {
                            img: "https://shp.qpic.cn/cfwebcap/0/f5fa39040a51d05bdd7587afdc1b5ebc/0/?width=230&height=140",
                            title: "【马菠萝奇闻录】第47期：我也不想出形昭啊，可他是老六诶！",
                            watch: 2970,
                        },
                        {
                            img: "https://shp.qpic.cn/cfwebcap/0/f5fa39040a51d05bdd7587afdc1b5ebc/0/?width=230&height=140",
                            title: "【马菠萝奇闻录】第47期：我也不想出形昭啊，可他是老六诶！",
                            watch: 2970,
                        },
                        {
                            img: "https://shp.qpic.cn/cfwebcap/0/f5fa39040a51d05bdd7587afdc1b5ebc/0/?width=230&height=140",
                            title: "【马菠萝奇闻录】第47期：我也不想出形昭啊，可他是老六诶！",
                            watch: 2970,
                        },
                        {
                            img: "https://shp.qpic.cn/cfwebcap/0/f5fa39040a51d05bdd7587afdc1b5ebc/0/?width=230&height=140",
                            title: "【马菠萝奇闻录】第47期：我也不想出形昭啊，可他是老六诶！",
                            watch: 2970,
                        },
                        {
                            img: "https://shp.qpic.cn/cfwebcap/0/f5fa39040a51d05bdd7587afdc1b5ebc/0/?width=230&height=140",
                            title: "【马菠萝奇闻录】第47期：我也不想出形昭啊，可他是老六诶！",
                            watch: 2970,
                        },
                        {
                            img: "https://shp.qpic.cn/cfwebcap/0/f5fa39040a51d05bdd7587afdc1b5ebc/0/?width=230&height=140",
                            title: "【马菠萝奇闻录】第47期：我也不想出形昭啊，可他是老六诶！",
                            watch: 2970,
                        },
                        {
                            img: "https://shp.qpic.cn/cfwebcap/0/f5fa39040a51d05bdd7587afdc1b5ebc/0/?width=230&height=140",
                            title: "【马菠萝奇闻录】第47期：我也不想出形昭啊，可他是老六诶！",
                            watch: 2970,
                        },
                    ]
                },
                {
                    value: "超神快讯+1",
                    content: [
                        {
                            img: "https://shp.qpic.cn/cfwebcap/0/298b55b64b149999f5884b92b2c9e884/0/?width=230&height=140",
                            title: "【狄仁杰封神榜】第89期 锁定透视 守护峡谷草丛！",
                            watch: 6786
                        },
                        {
                            img: "https://shp.qpic.cn/cfwebcap/0/298b55b64b149999f5884b92b2c9e884/0/?width=230&height=140",
                            title: "【狄仁杰封神榜】第89期 锁定透视 守护峡谷草丛！",
                            watch: 6786
                        },
                        {
                            img: "https://shp.qpic.cn/cfwebcap/0/298b55b64b149999f5884b92b2c9e884/0/?width=230&height=140",
                            title: "【狄仁杰封神榜】第89期 锁定透视 守护峡谷草丛！",
                            watch: 6786
                        },
                        {
                            img: "https://shp.qpic.cn/cfwebcap/0/298b55b64b149999f5884b92b2c9e884/0/?width=230&height=140",
                            title: "【狄仁杰封神榜】第89期 锁定透视 守护峡谷草丛！",
                            watch: 6786
                        },
                        {
                            img: "https://shp.qpic.cn/cfwebcap/0/298b55b64b149999f5884b92b2c9e884/0/?width=230&height=140",
                            title: "【狄仁杰封神榜】第89期 锁定透视 守护峡谷草丛！",
                            watch: 6786
                        },
                        {
                            img: "https://shp.qpic.cn/cfwebcap/0/298b55b64b149999f5884b92b2c9e884/0/?width=230&height=140",
                            title: "【狄仁杰封神榜】第89期 锁定透视 守护峡谷草丛！",
                            watch: 6786
                        },
                        {
                            img: "https://shp.qpic.cn/cfwebcap/0/298b55b64b149999f5884b92b2c9e884/0/?width=230&height=140",
                            title: "【狄仁杰封神榜】第89期 锁定透视 守护峡谷草丛！",
                            watch: 6786
                        },
                        {
                            img: "https://shp.qpic.cn/cfwebcap/0/298b55b64b149999f5884b92b2c9e884/0/?width=230&height=140",
                            title: "【狄仁杰封神榜】第89期 锁定透视 守护峡谷草丛！",
                            watch: 6786
                        },
                    ]
                },
                {
                    value: "绝对王者",
                    content: [
                        {
                            img: "https://shp.qpic.cn/cfwebcap/0/d28f038214234eaa82459c18ad7a9e77/0/?width=230&height=140",
                            title: "峡谷大气层 | 你知道赵云出了血魔之怒意味着什么吗？",
                            watch: 2970,
                        },
                        {
                            img: "https://shp.qpic.cn/cfwebcap/0/d28f038214234eaa82459c18ad7a9e77/0/?width=230&height=140",
                            title: "峡谷大气层 | 你知道赵云出了血魔之怒意味着什么吗？",
                            watch: 2970,
                        },
                        {
                            img: "https://shp.qpic.cn/cfwebcap/0/d28f038214234eaa82459c18ad7a9e77/0/?width=230&height=140",
                            title: "峡谷大气层 | 你知道赵云出了血魔之怒意味着什么吗？",
                            watch: 2970,
                        },
                        {
                            img: "https://shp.qpic.cn/cfwebcap/0/d28f038214234eaa82459c18ad7a9e77/0/?width=230&height=140",
                            title: "峡谷大气层 | 你知道赵云出了血魔之怒意味着什么吗？",
                            watch: 2970,
                        },
                        {
                            img: "https://shp.qpic.cn/cfwebcap/0/d28f038214234eaa82459c18ad7a9e77/0/?width=230&height=140",
                            title: "峡谷大气层 | 你知道赵云出了血魔之怒意味着什么吗？",
                            watch: 2970,
                        },
                        {
                            img: "https://shp.qpic.cn/cfwebcap/0/d28f038214234eaa82459c18ad7a9e77/0/?width=230&height=140",
                            title: "峡谷大气层 | 你知道赵云出了血魔之怒意味着什么吗？",
                            watch: 2970,
                        },
                        {
                            img: "https://shp.qpic.cn/cfwebcap/0/d28f038214234eaa82459c18ad7a9e77/0/?width=230&height=140",
                            title: "峡谷大气层 | 你知道赵云出了血魔之怒意味着什么吗？",
                            watch: 2970,
                        },
                        {
                            img: "https://shp.qpic.cn/cfwebcap/0/d28f038214234eaa82459c18ad7a9e77/0/?width=230&height=140",
                            title: "峡谷大气层 | 你知道赵云出了血魔之怒意味着什么吗？",
                            watch: 2970,
                        }
                    ]
                },
            ]
        },
        {
            title: "英雄攻略",
            optionList: [
                {
                    value: "选择英雄",
                    content: [
                        {
                            img: "https://shp.qpic.cn/cfwebcap/0/d28f038214234eaa82459c18ad7a9e77/0/?width=230&height=140",
                            title: "峡谷大气层 | 你知道赵云出了血魔之怒意味着什么吗？",
                            watch: 2970,
                        },
                        {
                            img: "https://shp.qpic.cn/cfwebcap/0/d28f038214234eaa82459c18ad7a9e77/0/?width=230&height=140",
                            title: "峡谷大气层 | 你知道赵云出了血魔之怒意味着什么吗？",
                            watch: 2970,
                        },
                        {
                            img: "https://shp.qpic.cn/cfwebcap/0/d28f038214234eaa82459c18ad7a9e77/0/?width=230&height=140",
                            title: "峡谷大气层 | 你知道赵云出了血魔之怒意味着什么吗？",
                            watch: 2970,
                        },
                        {
                            img: "https://shp.qpic.cn/cfwebcap/0/d28f038214234eaa82459c18ad7a9e77/0/?width=230&height=140",
                            title: "峡谷大气层 | 你知道赵云出了血魔之怒意味着什么吗？",
                            watch: 2970,
                        },
                        {
                            img: "https://shp.qpic.cn/cfwebcap/0/d28f038214234eaa82459c18ad7a9e77/0/?width=230&height=140",
                            title: "峡谷大气层 | 你知道赵云出了血魔之怒意味着什么吗？",
                            watch: 2970,
                        },
                        {
                            img: "https://shp.qpic.cn/cfwebcap/0/d28f038214234eaa82459c18ad7a9e77/0/?width=230&height=140",
                            title: "峡谷大气层 | 你知道赵云出了血魔之怒意味着什么吗？",
                            watch: 2970,
                        },
                        {
                            img: "https://shp.qpic.cn/cfwebcap/0/d28f038214234eaa82459c18ad7a9e77/0/?width=230&height=140",
                            title: "峡谷大气层 | 你知道赵云出了血魔之怒意味着什么吗？",
                            watch: 2970,
                        },
                        {
                            img: "https://shp.qpic.cn/cfwebcap/0/d28f038214234eaa82459c18ad7a9e77/0/?width=230&height=140",
                            title: "峡谷大气层 | 你知道赵云出了血魔之怒意味着什么吗？",
                            watch: 2970,
                        }
                    ]
                },
            ]
        },
    ]
)

/* 
    定义一个变量activeIndex1用来标记第一层嵌套 精品栏目 赛事精品 英雄攻略
    定义一个变量activeIndex2用来标记第二层嵌套 最新 峡谷大气层 ...
    每次activeIndex1的值变化时，activeIndex2的值都应该设置为初始值
*/
const activeIndex1 = ref(0)
const activeIndex2 = ref(0)
const changeActiveIndex1 = (index) => {
    // console.log(index)
    activeIndex1.value = index
    activeIndex2.value = 0
}

/* 
    定义一个方法changeActiveIndex2用来监听第二层嵌套的值变化
*/
const changeActiveIndex2 = (index) => {
    // console.log(index)
    activeIndex2.value = index
    console.log(activeIndex2.value);
}

/* 
    定义一个英雄数组，鼠标经过选择英雄按钮时，会出现
*/
const heroList = ref([
    {
        type: "热门",
        list: [
            {
                img: "	https://game.gtimg.cn/images/yxzj/img201606/heroimg/142/142.jpg",
                name: "安其拉"
            },
            {
                img: "	https://game.gtimg.cn/images/yxzj/img201606/heroimg/142/142.jpg",
                name: "安其拉"
            },
            {
                img: "	https://game.gtimg.cn/images/yxzj/img201606/heroimg/142/142.jpg",
                name: "安其拉"
            },
            {
                img: "	https://game.gtimg.cn/images/yxzj/img201606/heroimg/142/142.jpg",
                name: "安其拉"
            },
            {
                img: "	https://game.gtimg.cn/images/yxzj/img201606/heroimg/142/142.jpg",
                name: "安其拉"
            },
            {
                img: "	https://game.gtimg.cn/images/yxzj/img201606/heroimg/142/142.jpg",
                name: "安其拉"
            },
            {
                img: "	https://game.gtimg.cn/images/yxzj/img201606/heroimg/142/142.jpg",
                name: "安其拉"
            },
            {
                img: "	https://game.gtimg.cn/images/yxzj/img201606/heroimg/142/142.jpg",
                name: "安其拉"
            },
            {
                img: "	https://game.gtimg.cn/images/yxzj/img201606/heroimg/142/142.jpg",
                name: "安其拉"
            },
            {
                img: "	https://game.gtimg.cn/images/yxzj/img201606/heroimg/142/142.jpg",
                name: "安其拉"
            },
            {
                img: "	https://game.gtimg.cn/images/yxzj/img201606/heroimg/142/142.jpg",
                name: "安其拉"
            },
            {
                img: "	https://game.gtimg.cn/images/yxzj/img201606/heroimg/142/142.jpg",
                name: "安其拉"
            },
            {
                img: "	https://game.gtimg.cn/images/yxzj/img201606/heroimg/142/142.jpg",
                name: "安其拉"
            },
            {
                img: "	https://game.gtimg.cn/images/yxzj/img201606/heroimg/142/142.jpg",
                name: "安其拉"
            },
            {
                img: "	https://game.gtimg.cn/images/yxzj/img201606/heroimg/142/142.jpg",
                name: "安其拉"
            },

            {
                img: "	https://game.gtimg.cn/images/yxzj/img201606/heroimg/142/142.jpg",
                name: "安其拉"
            },
            {
                img: "	https://game.gtimg.cn/images/yxzj/img201606/heroimg/142/142.jpg",
                name: "安其拉"
            },
            {
                img: "	https://game.gtimg.cn/images/yxzj/img201606/heroimg/142/142.jpg",
                name: "安其拉"
            },
            {
                img: "	https://game.gtimg.cn/images/yxzj/img201606/heroimg/142/142.jpg",
                name: "安其拉"
            },
            {
                img: "	https://game.gtimg.cn/images/yxzj/img201606/heroimg/142/142.jpg",
                name: "安其拉"
            },
            {
                img: "	https://game.gtimg.cn/images/yxzj/img201606/heroimg/142/142.jpg",
                name: "安其拉"
            },
        ]
    },
    {
        type: "坦克",
        list: [
            {
                img: "https://game.gtimg.cn/images/yxzj/img201606/heroimg/533/533.jpg",
                name: "阿古朵"
            },
            {
                img: "https://game.gtimg.cn/images/yxzj/img201606/heroimg/533/533.jpg",
                name: "阿古朵"
            },
            {
                img: "https://game.gtimg.cn/images/yxzj/img201606/heroimg/533/533.jpg",
                name: "阿古朵"
            },
            {
                img: "https://game.gtimg.cn/images/yxzj/img201606/heroimg/533/533.jpg",
                name: "阿古朵"
            },
            {
                img: "https://game.gtimg.cn/images/yxzj/img201606/heroimg/533/533.jpg",
                name: "阿古朵"
            },
            {
                img: "https://game.gtimg.cn/images/yxzj/img201606/heroimg/533/533.jpg",
                name: "阿古朵"
            },
            {
                img: "https://game.gtimg.cn/images/yxzj/img201606/heroimg/533/533.jpg",
                name: "阿古朵"
            },
            {
                img: "https://game.gtimg.cn/images/yxzj/img201606/heroimg/533/533.jpg",
                name: "阿古朵"
            },
            {
                img: "https://game.gtimg.cn/images/yxzj/img201606/heroimg/533/533.jpg",
                name: "阿古朵"
            },
            {
                img: "https://game.gtimg.cn/images/yxzj/img201606/heroimg/533/533.jpg",
                name: "阿古朵"
            },
            {
                img: "https://game.gtimg.cn/images/yxzj/img201606/heroimg/533/533.jpg",
                name: "阿古朵"
            },
            {
                img: "https://game.gtimg.cn/images/yxzj/img201606/heroimg/533/533.jpg",
                name: "阿古朵"
            },
            {
                img: "https://game.gtimg.cn/images/yxzj/img201606/heroimg/533/533.jpg",
                name: "阿古朵"
            },

            {
                img: "https://game.gtimg.cn/images/yxzj/img201606/heroimg/533/533.jpg",
                name: "阿古朵"
            },
            {
                img: "https://game.gtimg.cn/images/yxzj/img201606/heroimg/533/533.jpg",
                name: "阿古朵"
            },
            {
                img: "https://game.gtimg.cn/images/yxzj/img201606/heroimg/533/533.jpg",
                name: "阿古朵"
            },
            {
                img: "https://game.gtimg.cn/images/yxzj/img201606/heroimg/533/533.jpg",
                name: "阿古朵"
            },
            {
                img: "https://game.gtimg.cn/images/yxzj/img201606/heroimg/533/533.jpg",
                name: "阿古朵"
            },
            {
                img: "https://game.gtimg.cn/images/yxzj/img201606/heroimg/533/533.jpg",
                name: "阿古朵"
            },
            {
                img: "https://game.gtimg.cn/images/yxzj/img201606/heroimg/533/533.jpg",
                name: "阿古朵"
            },
            {
                img: "https://game.gtimg.cn/images/yxzj/img201606/heroimg/533/533.jpg",
                name: "阿古朵"
            },
            {
                img: "https://game.gtimg.cn/images/yxzj/img201606/heroimg/533/533.jpg",
                name: "阿古朵"
            },
            {
                img: "https://game.gtimg.cn/images/yxzj/img201606/heroimg/533/533.jpg",
                name: "阿古朵"
            },
            {
                img: "https://game.gtimg.cn/images/yxzj/img201606/heroimg/533/533.jpg",
                name: "阿古朵"
            },
            {
                img: "https://game.gtimg.cn/images/yxzj/img201606/heroimg/533/533.jpg",
                name: "阿古朵"
            },
            {
                img: "https://game.gtimg.cn/images/yxzj/img201606/heroimg/533/533.jpg",
                name: "阿古朵"
            },
            {
                img: "https://game.gtimg.cn/images/yxzj/img201606/heroimg/533/533.jpg",
                name: "阿古朵"
            },
            {
                img: "https://game.gtimg.cn/images/yxzj/img201606/heroimg/533/533.jpg",
                name: "阿古朵"
            },
            {
                img: "https://game.gtimg.cn/images/yxzj/img201606/heroimg/533/533.jpg",
                name: "阿古朵"
            },
            {
                img: "https://game.gtimg.cn/images/yxzj/img201606/heroimg/533/533.jpg",
                name: "阿古朵"
            },

        ]
    },
    {
        type: "战士",
        list: []
    },
    {
        type: "刺客",
        list: []
    },
    {
        type: "法师",
        list: []
    },
    {
        type: "射手",
        list: []
    },
    {
        type: "辅助",
        list: []
    },
])

/* 
    定义一个变量用来控制英雄盒子的显示与隐藏
    定义一个变量用来控制英雄的类别
    定义一个函数用来展示不同类别的英雄
*/
const heroDivFlag = ref(false)
const heroActiveIndex = ref(0)
const changeHeroActiveIndex = (index) => {
    heroActiveIndex.value = index
}

const showHeroDiv = () => {
    heroDivFlag.value = true
}

const hideHeroDiv = () => {
    heroDivFlag.value = false
}

</script>
<template>
    <div class="content_center">
        <HomeModuleTitle title="内容中心" width="0" height="-107"></HomeModuleTitle>
        <div class="content">
            <!-- 第一层嵌套 精品栏目 赛事精品 英雄攻略 -->
            <div class="conten_top">
                <div style="position: relative;" class="li" @mouseover="changeActiveIndex1(index)"
                    :class="{ active1: activeIndex1 === index }" v-for="(item, index) in contentList" :key="index">
                    {{ item.title }}
                    <span class="split" v-show="index < 5"></span>
                </div>
            </div>
            <!-- 第二层嵌套 最新 峡谷大气层 ... -->
            <div class="BoutiqueColumn">
                <ul>
                    <!-- li:hover -->
                    <!-- 精品栏目和赛事精品 -->
                    <li @mouseover="changeActiveIndex2(index)"
                        v-for="(item, index) in contentList[activeIndex1].optionList" :key="index"
                        :class="activeIndex1 < 2 ? 'index01' : 'index2'">
                        <div class="div" @mouseover="showHeroDiv" @mouseout="hideHeroDiv">
                            {{ item.value }}
                            <i v-show="activeIndex1 === 2" class="iconfont icon-sanjiaodown"></i>
                        </div>
                        <!-- 鼠标经过英雄类型时出现的展示所有英雄的盒子 -->
                        <div @mouseover="showHeroDiv" @mouseout="hideHeroDiv"
                            v-show="activeIndex1 === 2 && heroDivFlag === true" class="hero">
                            <!-- 左边 -->
                            <div class="left">
                                <div @mousemove="changeHeroActiveIndex(index)" class="leftLi"
                                    v-for="(item, index) in heroList" :key="index">{{ item.type }}</div>
                            </div>
                            <!-- 右边 -->
                            <div class="right scroll-container">
                                <div class="everyHero" v-for="(item, index) in heroList[heroActiveIndex].list"
                                    :key="index">
                                    <img :src="item.img" alt="" width="60px">
                                    <p>{{ item.name }}</p>
                                </div>
                            </div>
                        </div>
                    </li>
                </ul>
            </div>
            <!-- 第三层嵌套 8个视频 -->
            <ul class="BoutiqueColumnVideos">
                <li v-for="(item, index) in contentList[activeIndex1].optionList[activeIndex2].content" :key="index">
                    <img :src="item.img" alt="">
                    <div class="bottom">
                        <!-- 灰色蒙层 -->
                        <span class="mask">
                            <i class="iconfont icon-shipinbofang-"></i>
                            {{ item.watch }}
                        </span>
                        <span class="title">{{ item.title }}</span>
                    </div>
                    <!-- 鼠标经过时的灰色蒙层和精灵图上截取下来的播放图标展示 -->
                    <div class="videoHover">
                        <div></div>
                    </div>
                </li>
            </ul>
        </div>
    </div>
</template>
<style scoped>
.split {
    position: absolute;
    right: 0;
    width: 1px;
    height: 20px;
    overflow: hidden;
    background: #e1e1e1;
    display: inline-block;
}

.active1 {
    border-bottom: 3px solid #f3c258;
    color: #333333 !important;
}

.active2 {
    border-color: #f3c258;
    background-color: #f3c258;
    color: #fff;
}

.content_center {
    height: 100%;
    width: 872px;
    display: flex;
    flex-direction: column;

    .content {
        flex: 1;
        width: 100%;

        .conten_top {
            width: 872px;
            height: 32px;
            background-color: grey;
            display: flex;

            .li {
                width: 33.333333333333333333%;
                height: 100%;
                display: flex;
                justify-content: center;
                align-items: center;
                font-size: 14px;
                color: #999;
                background-color: #f5f5f5;
            }

            li:nth-child(2n) {
                border-right: 1px solid #999;
                border-left: 1px solid #999;
            }
        }

        .BoutiqueColumn {
            width: 100%;
            height: 67px;

            ul {
                width: 100%;
                height: 100%;
                display: flex;
                align-items: center;
                margin-left: 9px;

                .index01 {
                    height: 28px;
                    line-height: 28px;
                    padding: 0 18px 0 18px;
                    border: 1px solid #e5e5e5;
                    border-radius: 10px;
                    background-color: #f5f5f5;
                    font-size: 14px;
                    color: #333;
                    margin-right: 8px;
                    display: inline-block;
                    margin-bottom: 5px;
                }

                .index2 {
                    position: absolute;
                    width: 104px;
                    height: 26px;

                    .div {
                        padding-left: 10px;
                        display: flex;
                        align-items: center;
                        font-size: 14px;

                        i {
                            margin-left: 3px;
                            color: #f3c258;
                        }
                    }

                    .hero {
                        position: absolute;
                        width: 872px;
                        height: 337px;
                        left: -9px;
                        top: 25px;
                        z-index: 99;
                        display: flex;
                        background-color: #fff;

                        .left {
                            width: 78px;
                            /* height: 42px; */
                            height: 100%;
                            background-color: #F5F5F5;

                            .leftLi {
                                width: 100%;
                                height: 42px;
                                display: flex;
                                justify-content: center;
                                align-items: center;
                                flex-direction: column;
                            }

                            .leftLi:hover {
                                background-color: #f3c258;
                                color: #fff;
                            }
                        }

                        /* 给盒子加滚动条 */
                        .scroll-container {
                            height: 200px;
                            /* 设置固定高度 */
                            overflow-y: auto;
                            /* 当内容超出高度时显示垂直滚动条 */
                            /* 可视边界 */
                        }

                        .right {
                            width: 768px;
                            margin-left: 26px;
                            height: 100%;
                            background-color: #fff;
                            display: flex;
                            flex-wrap: wrap;
                            padding-top: 11px;

                            .everyHero {
                                margin: 0 26px 26px 0;
                                width: 60px;
                                height: 86px;
                                display: flex;
                                flex-direction: column;
                                justify-content: center;
                                align-items: center;
                            }
                        }
                    }
                }

                .index01:hover {
                    border-color: #f3c258;
                    background-color: #f3c258;
                    color: #fff;
                }

            }
        }

        .BoutiqueColumnVideos {
            width: 100%;
            flex: 1;
            display: flex;
            flex-wrap: wrap;
            justify-content: space-between;

            li {
                width: 209px;
                height: 175px;
                margin-bottom: 30px;
                position: relative;

                img {
                    width: 209px;
                    height: 125px;
                }

                .bottom {
                    margin-top: 10px;
                    position: relative;

                    .title {
                        color: #333333;
                        font-size: 14px;
                    }

                    .mask {
                        display: flex;
                        align-items: center;
                        position: absolute;
                        top: -33px;
                        left: 0;
                        width: 209px;
                        height: 22px;
                        line-height: 22px;
                        padding: 0 10px;
                        color: #fff;
                        background: rgba(0, 0, 0, 0.6);
                        font-size: 12px;
                        border-radius: 0 0 2px 2px;

                        i {
                            margin-right: 3px;
                        }
                    }
                }
            }

            li:hover {
                .videoHover {
                    position: absolute;
                    width: 209px;
                    height: 125px;
                    background: rgba(0, 0, 0, 0.6);
                    left: 0;
                    top: 0;

                    div {
                        background: url(//game.gtimg.cn/images/yxzj/web201706/images/comm/index.png) no-repeat;
                        width: 40px;
                        height: 40px;
                        display: block;
                        margin: 40px auto 0;
                        background-position: -192px -64px;
                    }
                }
            }
        }
    }
}
</style>