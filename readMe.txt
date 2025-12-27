RomeTotalWar Remaster Mod 


建筑按照派系 可招募部队 可参考 building temple_of_justice


		temple_of_justice_awesome_temple requires factions { carthaginian, egyptian, } 
		{
			;;conditions under which the AI will destroy this building
			ai_destruction_hint requires not factions { carthaginian, egyptian, }

			capability
			{
				recruit "barb druids gaul"  0
				recruit "barb naked fanatics spain"  0
				recruit "spanish bull warriors"  0
				recruit "carthaginian sacred band infantry"  0
				happiness_bonus bonus 4
				law_bonus bonus 4
			}
			construction  5 
			cost  3200 
			settlement_min large_city
			upgrades
			{
				temple_of_justice_pantheon
			}
		}

作弊码	影响
？	获取输入的作弊码的帮助
add_money ##	通过##增加资金
add_population	将人口添加到输入的城市
adjust_sea_bed	调整海床高度
ai_turn_speed	设置AI转速
auto_win	攻击者或后卫自动解决战斗
burn_piggies_burn	点燃所有贪婪的眨眼
capture_settlement	捕获输入的城市
character_reset	将字符重置为开始设置
clear_messages	清除所有消息
create_building	创建输入类型的建筑物
create_unit	在选择或角色部队中创建一个单位
damage_wall	破坏定居点的墙壁
diplomacy_mission	创建外交使命
diplomatic_stance	设置两派的外交立场
disable_ai	禁用AI
filter_coastlines	将滤镜应用于世界地图海岸线
force_battle_defeat	强制玩家失败
force_battle_victory	强制玩家赢得这场战斗
force_diplomacy	强迫对手接受外交建议
gamestop或bestbuy	在广告系列模式下使单位更便宜10％
give_trait	给角色特质
give_trait_points	给角色特质
give_trait_points	给角色特定的特质点
halt_ai	停止AI转动顺序
invulnerable_general	在战斗中一般无敌
kill_character	杀死角色
kill_faction	杀派
list_ancillaries	列出所有可用的辅助设备
list_characters	列出游戏中的所有角色
list_traits	列出所有特征
list_units	列出军队中的所有单位
move_character	将角色移至地图坐标
oliphaunt	在竞选模式下让大象增加40％
output_unit_positions	显示所有战斗单位的位置
process_cq	完成施工队列中的所有建筑物
process_rq	在招募队列中完成所有军事单位
regenerate_radar	再生雷达
run_ai	重新开始AI转动（在停止后--see halt_ai）
set_building_health	设置建筑健康
show_all_messages	切换显示所有消息给所有派系
show_battle_circle	在r半径的x，y处显示一个圆圈t秒
show_battle_marker	在x，y上显示一个标记t秒
show_battle_street_plan	显示解决方案的街道计划
toggle_coastlines	切换海岸线显示
toggle_flowing_water	在活动地图上切换流水的显示
toggle_fow	切换战争迷雾
toggle_overlay	切换覆盖
toggle_perfect_spy	切换侦察能力
toggle_restrictcam	切换相机限制
toggle_terrain	切换地形
trigger_advice	触发建议
upgrade_effect	触发单元升级


作弊码中输入地点具体字符串
{Britannia_Inferior}	下不列颠
{Tribus_Saxones}	撒克逊
{Locus_Gepidae}	格皮德
{Hyperboria}	北国
{Tribus_Sakae}	塞克
{Hibernia}	希伯尼亚
{Tribus_Alanni}	阿兰尼
{Tribus_Silurii}	西卢里
{Locus_Gothi}	哥特
{Tribus_Sarmatae}	萨尔马提亚
{Britannia_Superior}	上不列颠
{Germania_Inferior}	下日耳曼
{Tribus_Chattii}	卡狄
{Pripet}	普利佩特
{Regnum_Marcomannii}	马科曼尼
{Belgica}	贝尔吉卡
{Maeotis}	梅欧提斯
{Agri_Decumates}	阿格里狄古马特
{Armorica}	阿莫里卡
{Germania_Superior}	上日耳曼
{Boihaemum}	波海姆
{Scythia}	西徐亚
{Tribus_Iazyges}	雅斯基
{Central_Gaul}	大高卢
{Dacia}	达西亚
{Noricum}	诺里库姆
{Tribus_Getae}	加泰
{Pannonia}	潘诺尼亚
{Bosphorus}	博斯普鲁斯
{Aquitania}	阿奎塔尼
{Lugdinensis}	卢格杜南西斯
{Colchis}	科尔基思
{Atropatene}	阿特洛帕特内
{Cisalpine_Gaul}	山内高卢
{Venetia}	威尼托
{Transalpine_Gaul}	山外高卢
{Illyria}	伊利里亚
{Thrace}	色雷斯
{Gallaecia}	加利西亚
{Dalmatia}	达尔马提亚
{Armenia}	亚美尼亚
{Narbonensis}	那尔傍高卢
{Liguria}	雷古利亚
{Pontus}	本都
{Celtiberia}	坎特伯雷
{Paionia}	派奥尼亚
{Etruria}	伊特鲁利亚
{Taraconenis}	塔拉戈南尼斯
{Umbria}	乌布里亚
{Media}	米底亚
{Lusitania}	卢西塔尼亚
{Sardinia}	撒丁岛
{Latium}	拉丁
{Macedonia}	马其顿
{Propontis}	普罗庞提斯
{Bithynia}	比提尼亚
{Galatia}	加拉太
{Cappadocia}	卡帕多西亚
{Hispania}	伊比利亚
{Epirus}	伊庇鲁斯
{Apulia}	阿普里亚
{Campania}	坎帕尼亚
{Assyria}	亚述
{Baetica}	贝提卡
{Phrygia}	弗里吉亚
{Cilicia}	西里西亚
{Thessalia}	色萨利
{Baliares}	巴利阿里群岛
{Bruttium}	布鲁提恩
{Ionia}	爱奥尼亚
{Syria}	叙利亚
{Babylonia}	巴比伦尼亚
{Aetolia}	埃托里亚
{Attica}	阿提卡
{Elymais}	以莱美斯
{Peloponnesus}	伯罗奔尼撒
{Lycia}	吕西亚
{Sicilia_Romanus}	上西西里亚
{Sicilia_Poeni}	下西西里亚
{Mauretania}	毛里塔尼亚
{Regnum_Palmyrae}	帕米拉
{Cyprus}	塞浦路斯岛
{Phoenicia}	腓尼基
{Numidia}	努米底亚
{Africa}	阿非利加
{Sicilia_Graecus}	大西西里
{Laconia}	拉科尼亚
{Coele_Syria}	科罗叙利亚
{Rhodos}	罗德斯岛
{Arabia}	阿拉伯
{Byzacium}	拜萨西恩
{Crete}	克里特岛
{Nabataea}	纳巴泰
{Judaea}	犹太
{Gaetulia}	加图里亚
{Tripolitania}	的黎波里塔尼亚
{Cyrenaica}	昔兰尼加
{Nile_Delta}	尼罗河三角洲
{Sinai}	西奈山
{Libya}	利比亚
{Middle_Egypt}	中埃及
{Sahara}	撒哈拉
{Thebais}	底比斯
{Eburacum}	埃波拉克
{Bordesholm}	博登肖姆
{Domus_Dulcis_Domus}	杜尔西斯
{Themiskyra}	塞米斯卡拉
{Campus_Sakae}	塞克
{Tara}	塔拉
{Campus_Alanni}	阿兰尼
{Deva}	迪瓦
{Vicus_Gothi}	哥特
{Campus_Sarmatae}	萨尔马特
{Londinium}	隆迪尼恩
{Batavodurum}	巴达维
{Damme}	达姆
{Vicus_Venedae}	威尼达
{Vicus_Marcomannii}	马科曼尼
{Samarobriva}	萨马罗布里瓦
{Tanais}	塔奈斯
{Mogontiacum}	美因茨
{Condate_Redonum}	雷恩
{Trier}	特里尔
{Lovosice}	洛沃西采
{Campus_Scythii}	西徐亚
{Campus_Iazyges}	雅斯基
{Alesia}	阿莱西亚
{Porrolissum}	波罗里森
{Iuvavum}	萨尔茨堡
{Campus_Getae}	加泰
{Aquincum}	阿昆克
{Chersonesos}	切索尼斯
{Lemonum}	里蒙
{Lugdunum}	卢格敦
{Kotais}	库塔伊西
{Phraaspa}	弗拉斯帕
{Mediolanium}	米迪奥拉努姆
{Patavium}	帕多瓦
{Massilia}	马西利亚
{Segestica}	塞吉斯提卡
{Tylis}	泰里斯
{Asturica}	阿斯图里加
{Salona}	萨罗讷
{Artaxarta}	阿尔塔沙特
{Narbo_Martius}	纳尔榜玛提厄斯
{Segesta}	塞吉斯塔
{Sinope}	锡诺普
{Numantia}	努曼提亚
{Bylazora}	贝拉索拉
{Arretium}	亚雷提恩
{Osca}	奥斯卡
{Ariminum}	亚里米伦
{Arsakia}	阿萨基亚
{Scallabis}	斯卡拉比斯
{Caralis}	卡拉里斯
{Roma}	罗马
{Thessalonica}	塞萨洛尼卡
{Byzantium}	拜占庭
{Nicomedia}	尼科米底亚
{Ancyra}	安卡拉
{Mazaka}	马萨卡
{Carthago_Nova}	新迦太基
{Apollonia}	阿波罗尼亚
{Tarentum}	塔伦图姆
{Capua}	卡普亚
{Hatra}	哈特拉
{Corduba}	科尔多巴
{Pergamum}	珀加蒙
{Tarsus}	塔尔苏斯
{Larissa}	拉里萨
{Palma}	帕尔马
{Croton}	克罗顿
{Sardis}	萨狄斯
{Antioch}	安条克
{Seleucia}	塞琉西亚
{Thermon}	色蒙
{Athens}	雅典
{Susa}	苏撒
{Corinth}	科林斯
{Halicarnasus}	哈利卡纳苏斯
{Messana}	墨西拿
{Lilybaeum}	利利俾
{Tingi}	丹吉尔
{Palmyra}	帕米拉
{Salamis}	萨拉米斯
{Sidon}	西顿
{Cirta}	瑟塔
{Carthage}	迦太基
{Syracuse}	叙拉古
{Sparta}	斯巴达
{Damascus}	大马士革
{Rhodes}	罗德斯
{Dumatha}	杜马萨
{Thapsus}	塔普苏斯
{Kydonia}	科多尼亚
{Bostra}	波斯卓
{Jerusalem}	耶路撒冷
{Dimmidi}	底米迪
{Lepcis_Magna}	大列普提斯
{Cyrene}	昔兰尼
{Alexandria}	亚历山大
{Petra}	佩特拉
{Siwa}	锡瓦
{Memphis}	孟斐斯
{Nepte}	涅普特
{Thebes}	底比斯
{Rome}	罗马
