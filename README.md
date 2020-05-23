```python
import pandas as pd
pd.set_option('display.max_rows', 500)
pd.set_option('display.max_columns', 500)
pd.set_option('display.width', 1000)
```


```python
ct = '54ztv9yyx8u3s5u1xvutrvu414y1vzztxvutrv84xvutrvvux3uvrvurxv9w22v48wutrvuw07y2vzys2z014984267uw0wu0wu5v7xwyzyvs09v1vu6t42sx941zvu1axutr0zrxvuy6v660ax0uv104y1w0x7x76665954261v632u6285455t07v3345ty7u7sa1ub80t5895c9171572a674468s9a9zyww4b89y60vw9612y51185z1vxvu9y38y1xs6wz308356a38xa0539x3u1yr9a744672z68wuwvz578y27568a48yz2xz12z060za602y66x47w20w515612y31z3373vvxzc93w3vy07935v94yx86yrx7r1861426y4v16v38u2701638r7a8tz86yby9uw6uv65yyvz7169605v7r009u03y090wzrxxyb2xur0ux712zxz4x4714y21y8218s9w6zx7vw09sc3082z6y926060y09077y363y79xz26ycavuzavsbv5usw061354u89rc3z42zv6y90841z529z72vvr67x2192x929t3404xau8668t0w5vvv4wcaz5u75x6927r87r98u8336y7azzv926z41x63yr1y23r13x6z7ys1337611xx0wy560y4xs871wuxyr9y1t406z2123z06t5360wy4wxvu3t702y51xrvxw2x60uw6vyy36329s0780t80u83xxy1zr5xw1y423b0uxs9uyx497s1346wzz54w20zw84225zw2vszu41yv54003xx9x52xs911y56vux476u3333v4v460yb9w05x8uyw52r6y2byw425x160y4s96225z327426x16v6v20z40vv1ua66t012vxy44u81400203a2sy62xsaxx7a9y19vsx6vtrxu68z6t6v332y8xy4ws2a04sz2x9v36ra2s0vv2s4zt62u7w7z11xx8s9zu5w6txy8zzvvz256w102w173z96u5u5yr1y47330y4wvw1vwy29u2v165a3w0sxxr5wy3rw7t9a58u7263yuvrau00775u3020y281wys24v5wvvvx44y165r49y7ww71za51svvv7y6t4494289zr91yy130z44w8zyts8yt644uwv7vx78xy11r53y5zvz105943ywx27v6s98y619wr51tzvw5w11x4z15w37xx8ztrzuw1zy3za6115vvt32448u1w236137xuy0y1538u8405508saww8332325t15w0188sz7y7tax127u16vv3660yx1vyya7xy54y4355wzw328185vw4xxu04y3s3207u753901tx20y844034uya760051rz82632zv8xz5ta8u707wzv5s0yx1rax113w42wx6b20z0z8xxy40v75r53y1xz16x3ux523v831xz0837v72r1v3y3v51v3u69yw234389213234668ur61z2723t0u2cy836z611w2w446r1x5vv5yucvxzuv03978ws79z328uw561byxvua1x0avuvz9r20u5wz0vy0084vysc96ztw4w76zwxw16008tyw3613yvs9160w546666977y50vv5a2yy9wx9wvxza30935wz74wx70222x3b13t14zuzv8wt08ux83wua6629yx2x3r8ww55x1sx247r61z07zy1auz9wvy174tcxu7swxvcz6xx4w15913y1w2axy8040rz43u3xus650009760737485t721107uy617w36743046089uy39zs9v3xwx6200r6wwx3z0049874z7415v7u28s852t322ub142z07xb91u453u55wzzavw9300y473zzvvyw9x6xuyry610448034w93zxw97s4www64zr017yu91097ww5v1z05w7sa2v213632zs9x71v74rz128661r788x2w92544zxv2s1a4ww7544vzts993c98uzx537x582wx24z58v63u89yyx146ax6703046v2858zuay30z47v6912v77431y4367vaa30tvu1511v5awty9905wz19y0wxx8t873xt1vrb663yyvx77w137x546676y40x2x559vu54xy26vta0yww4ww2w02uyyy651u2w4x9a8w4x4z068uuw5vx5vy2z155828ux62ay68s5v5620wyyx4zw9w231356u6z2115174t99t7a45s43y1v3yr53r2wwuy3u64355z3yz1w45xx969wu8t3z52xu2swywz665v0ys07zx439x76v6u86384953yzy6643w62y654y41v0155z2zyv247v316u966xv5725968yv454vvyv2vx612yz9vt1y863990x91vs1w55866swzs7a6vyz3v7a34241t2zztw9104a92xy408vw0534yb52u0z5167w4169w18wvt4z0a2vwx1x2b294u715c2z4wv56623zw63v820ys3wz2vxtuwwxx396y0yy7344wzw35461x504avww6avyxv4u6w522v9045633y70wax46223s0zz9w8236ux8064z6913746t4u3cy9y2xz602u55vvt9y9542uvc3v5x91y62970z35x22wuxwuy505wv8s29v3r53vb4y3z49xzxwvvw9tc47z3y45b632x493xx860a1vav933a6z25utrvurxvy2v0y51z47vx0r5x'
ct1 = '5zvyxusuxuru1yvzxur8xurvxurux92v8uru0yvy204827ww0uvxyys91ut2x4zuaurzxu660xu141077655216268450v35yus1b059c117a74899ywb96v91y18zvv93yx6z0363x03xuy9747z8uv582584y2z200a0y64w0551y137vxc33y73v4x6r7164641v8206878z6b9wu6yv76657090y9wrxbxru72x441y181swz7w9c026966y97y6y9z6cvzvb5s015u9cz2vy04z2z2v6x129930xu6805v4czu562r79u367zv2z16y12r367s371x0y6yx81uy914622z656w4xut0y1rx26u6y33908t08xyz5wy2busux9s36z5w0w42z2su1v40x95x915vx7u33440bw58y5rybw2x6ys62z2461vv04v1a602x4u10232y2sx791vxvru866328yw20s293r20vsz6uwz1xsz56x8zv2612139uuy14304v1w2uv6awsx5yr795u23uru07u0021y2vwvx4154yw7z5sv764929r1y3z48ysy64w7x8y15yzz093w2vs869r1zww141w7xzru1yz61vt24uw317u013u450sw83351w18zytx2u6v60xvy7y445ww215wxu4330u591x0843ua601z23z8zt877z50xrx1w2xb008x4v55yx1xu5381z877rvyv136y24823368r122tuc866124615vycxu098s938w6bxu10vv92uw0y04yc6t47zx108y31ys10566975v52yw9vz395z4x02xb31zz8t8x3u62y238w51x4r10z1u9v14cusxc6xw51yway00z33u60070345710u67373409y9svxx206w3048471vu88232b4z7b1435wzv90y7zvy96ur604049zw74w6z07u19w510ws2233z97v4z261782954x214w54zs9c8z5752x45v38yx4a600625za3z761v73y37a3tu515wy95z90x883tvb6yv7w3x4664xx5v5x2vayww20uy6124984408u5xv2152u6a6sv60yxz9215uz157t974s313r32wyu45zy14x99utz2usyz6vy0z497vu6893z64w2644v152y273696v756y44vvv62zv1839x1sw56sz76y373212zw149x48w54b2056w191wtzavxxb9u1czw563w380sw2xuwx9yy74ww56x0aw6vx465294637wx62sz983u86z934tuc92z0u5v994ucvx16903x2uwy0w82vr3byz9zwv9c734b3x9x801a9362uruxyvy14v05'
ct2 = '4t9y8351vtv441ztvtv4vtvu3vvrvw24wtvw72zsz1946u0uw57wzv0vv64s91v1xt0rvyv6a0v0ywxx66946v3u255t734t77au8t859752646sazw48y0w625151xuy81sw385a8a5931ra4626wwz7y76a8zx1z6z626x72w1623z33vz9wv0959y8yxr812yv63u713rat8yyu6v5yz190vr0u300zxy2u0x1zzx742y2896xv0s38zy200007337x2yauasvuw6348r34z6981597vr729x2t44a86twvvwa57x978r883yaz964x3ry31xzy1361xw504s7wxryt0z130t30ywv3725xvwx0wvy62s708u3x1rx1430x9y4714wz42z825wvz4y503xx2s1y6u4633vv6y90xuw262y45104925372x662z0vu6t1vy48400as6xaxay9s6tx6ztv3yx4sa4zxv6asv24t2771x89uwtyzvz5w0w7z655ry73ywwvy921530xrw3wta876yva07532y8ws45vv4y6r97w1a1vvyt448z9y104wzt8t4uvv7x1r35v154yx769y1w5tv51xz53x8tzwz3a15v3481263xyy588058aw322t508s77a171v36y1yax5y35z388v4x0ys27730t2y404y705r862vx5au0wvsy1a134w62zzxy07r31z63x2v3x03v21335vu9w3391246u6z7302y3z1ww4rxv5uvzv37w7z2u51yvaxauzr05zv08vs9zww6ww60tw63v96w4667y0vay9xwxa03w7w72231t4uvw0u8wa69xxrw5xs276z7yazwy7tx7wvzx419312x84r4uxs5096778t217y1w64068u3z93w60rwxz097z4572s5t2u120x9u5u5zaw3043zvwxxyy1483w3x9sww4r1y907wvz57av162sx17r186r8xw24zvsaw74vt939ux3x8w2z86u9y16x734v88uy04v9274146va0v11vat90w1ywxt7x1r63yx717567y0259u4y6t0w4ww2yy5uwxawxz6uwv5yz588x2y8552wy4ww336621149ta54yvy5rwu36353zw5x6w835x2ww650s7x3x668345yy636y5y105zzv4v1u6x5298v5vy2x1y9ty6909v1586wsavzva44tzt90a2y0v03y5uz1746w8v402w12247524v62z6v2y3zvtwx360y34z34154vwayvuw2v053y0a4230zw26x04617643yyx625vty52v359y27z52wxu55vs935v434xxvwt4zy56243x6avv3az5tvrv205z7xrx'
oxorig  = 'oxawgidx20vno61zgtlx3o7a7mha20w1zy6avx4ü39rwijn2jsuc0f2hs22oo6üβqh2c8py6o7v86cvygfm3zg664z3nzdw4ju7huhw69gfo0yx1xö4x27yfco5hs6cvfü3uajsejrxzag0vxzi4a1rü5wkwvij22hz4c603g9o0ejrpz5bi4w2juoumch2efmöcmy7oo9wb'
oxedit  = 'oxawgidx20vno61zgtlx3o7a7mha20w1zy6avx4u39rwijn2jsuc0f2hs22oo6ussqh2c8py6o7v86cvygfm3zg664z3nzdw4ju7huhw69gfo0yx1xo4x27yfco5hs6cvfu3uajsejrxzag0vxzi4a1ru5wkwvij22hz4c603g9o0ejrpz5bi4w2juoumch2efmocmy7oo9wb'
oxedit2 = 'oxawgidx20vno61zgtlx3o7a7mha20w1zy6avx4u39rwijn2jsuc0f2hs22oo6usqh2c8py6o7v86cvygfm3zg664z3nzdw4ju7huhw69gfo0yx1xo4x27yfco5hs6cvfu3uajsejrxzag0vxzi4a1ru5wkwvij22hz4c603g9o0ejrpz5bi4w2juoumch2efmocmy7oo9wb'
oxedit3 = 'oxawgidx20vno61zgtlx3o7a7mha20w1zy6avx439rwijn2jsuc0f2hs22oo6qh2c8py6o7v86cvygfm3zg664z3nzdw4ju7huhw69gfo0yx1x4x27yfco5hs6cvf3uajsejrxzag0vxzi4a1r5wkwvij22hz4c603g9o0ejrpz5bi4w2juoumch2efmcmy7oo9wb'
ctarr = ['54','zt','v9','yy','x8','u3','s5','u1','xv','ut','rv','u4','14','y1','vz','zt','xv','ut','rv','84','xv','ut','rv','vu','x3','uv','rv','ur','xv','9w','22','v4','8w','ut','rv','uw','07','y2','vz','ys','2z','01','49','84','26','7u','w0','wu','0w','u5','v7','xw','yz','yv','s0','9v','1v','u6','t4','2s','x9','41','zv','u1','ax','ut','r0','zr','xv','uy','6v','66','0a','x0','uv','10','4y','1w','0x','7x','76','66','59','54','26','1v','63','2u','62','85','45','5t','07','v3','34','5t','y7','u7','sa','1u','b8','0t','58','95','c9','17','15','72','a6','74','46','8s','9a','9z','yw','w4','b8','9y','60','vw','96','12','y5','11','85','z1','vx','vu','9y','38','y1','xs','6w','z3','08','35','6a','38','xa','05','39','x3','u1','yr','9a','74','46','72','z6','8w','uw','vz','57','8y','27','56','8a','48','yz','2x','z1','2z','06','0z','a6','02','y6','6x','47','w2','0w','51','56','12','y3','1z','33','73','vv','xz','c9','3w','3v','y0','79','35','v9','4y','x8','6y','rx','7r','18','61','42','6y','4v','16','v3','8u','27','01','63','8r','7a','8t','z8','6y','by','9u','w6','uv','65','yy','vz','71','69','60','5v','7r','00','9u','03','y0','90','wz','rx','xy','b2','xu','r0','ux','71','2z','xz','4x','47','14','y2','1y','82','18','s9','w6','zx','7v','w0','9s','c3','08','2z','6y','92','60','60','y0','90','77','y3','63','y7','9x','z2','6y','ca','vu','za','vs','bv','5u','sw','06','13','54','u8','9r','c3','z4','2z','v6','y9','08','41','z5','29','z7','2v','vr','67','x2','19','2x','92','9t','34','04','xa','u8','66','8t','0w','5v','vv','4w','ca','z5','u7','5x','69','27','r8','7r','98','u8','33','6y','7a','zz','v9','26','z4','1x','63','yr','1y','23','r1','3x','6z','7y','s1','33','76','11','xx','0w','y5','60','y4','xs','87','1w','ux','yr','9y','1t','40','6z','21','23','z0','6t','53','60','wy','4w','xv','u3','t7','02','y5','1x','rv','xw','2x','60','uw','6v','yy','36','32','9s','07','80','t8','0u','83','xx','y1','zr','5x','w1','y4','23','b0','ux','s9','uy','x4','97','s1','34','6w','zz','54','w2','0z','w8','42','25','zw','2v','sz','u4','1y','v5','40','03','xx','9x','52','xs','91','1y','56','vu','x4','76','u3','33','3v','4v','46','0y','b9','w0','5x','8u','yw','52','r6','y2','by','w4','25','x1','60','y4','s9','62','25','z3','27','42','6x','16','v6','v2','0z','40','vv','1u','a6','6t','01','2v','xy','44','u8','14','00','20','3a','2s','y6','2x','sa','xx','7a','9y','19','vs','x6','vt','rx','u6','8z','6t','6v','33','2y','8x','y4','ws','2a','04','sz','2x','9v','36','ra','2s','0v','v2','s4','zt','62','u7','w7','z1','1x','x8','s9','zu','5w','6t','xy','8z','zv','vz','25','6w','10','2w','17','3z','96','u5','u5','yr','1y','47','33','0y','4w','vw','1v','wy','29','u2','v1','65','a3','w0','sx','xr','5w','y3','rw','7t','9a','58','u7','26','3y','uv','ra','u0','07','75','u3','02','0y','28','1w','ys','24','v5','wv','vv','x4','4y','16','5r','49','y7','ww','71','za','51','sv','vv','7y','6t','44','94','28','9z','r9','1y','y1','30','z4','4w','8z','yt','s8','yt','64','4u','wv','7v','x7','8x','y1','1r','53','y5','zv','z1','05','94','3y','wx','27','v6','s9','8y','61','9w','r5','1t','zv','w5','w1','1x','4z','15','w3','7x','x8','zt','rz','uw','1z','y3','za','61','15','vv','t3','24','48','u1','w2','36','13','7x','uy','0y','15','38','u8','40','55','08','sa','ww','83','32','32','5t','15','w0','18','8s','z7','y7','ta','x1','27','u1','6v','v3','66','0y','x1','vy','ya','7x','y5','4y','43','55','wz','w3','28','18','5v','w4','xx','u0','4y','3s','32','07','u7','53','90','1t','x2','0y','84','40','34','uy','a7','60','05','1r','z8','26','32','zv','8x','z5','ta','8u','70','7w','zv','5s','0y','x1','ra','x1','13','w4','2w','x6','b2','0z','0z','8x','xy','40','v7','5r','53','y1','xz','16','x3','ux','52','3v','83','1x','z0','83','7v','72','r1','v3','y3','v5','1v','3u','69','yw','23','43','89','21','32','34','66','8u','r6','1z','27','23','t0','u2','cy','83','6z','61','1w','2w','44','6r','1x','5v','v5','yu','cv','xz','uv','03','97','8w','s7','9z','32','8u','w5','61','by','xv','ua','1x','0a','vu','vz','9r','20','u5','wz','0v','y0','08','4v','ys','c9','6z','tw','4w','76','zw','xw','16','00','8t','yw','36','13','yv','s9','16','0w','54','66','66','97','7y','50','vv','5a','2y','y9','wx','9w','vx','za','30','93','5w','z7','4w','x7','02','22','x3','b1','3t','14','zu','zv','8w','t0','8u','x8','3w','ua','66','29','yx','2x','3r','8w','w5','5x','1s','x2','47','r6','1z','07','zy','1a','uz','9w','vy','17','4t','cx','u7','sw','xv','cz','6x','x4','w1','59','13','y1','w2','ax','y8','04','0r','z4','3u','3x','us','65','00','09','76','07','37','48','5t','72','11','07','uy','61','7w','36','74','30','46','08','9u','y3','9z','s9','v3','xw','x6','20','0r','6w','wx','3z','00','49','87','4z','74','15','v7','u2','8s','85','2t','32','2u','b1','42','z0','7x','b9','1u','45','3u','55','wz','za','vw','93','00','y4','73','zz','vv','yw','9x','6x','uy','ry','61','04','48','03','4w','93','zx','w9','7s','4w','ww','64','zr','01','7y','u9','10','97','ww','5v','1z','05','w7','sa','2v','21','36','32','zs','9x','71','v7','4r','z1','28','66','1r','78','8x','2w','92','54','4z','xv','2s','1a','4w','w7','54','4v','zt','s9','93','c9','8u','zx','53','7x','58','2w','x2','4z','58','v6','3u','89','yy','x1','46','ax','67','03','04','6v','28','58','zu','ay','30','z4','7v','69','12','v7','74','31','y4','36','7v','aa','30','tv','u1','51','1v','5a','wt','y9','90','5w','z1','9y','0w','xx','8t','87','3x','t1','vr','b6','63','yy','vx','77','w1','37','x5','46','67','6y','40','x2','x5','59','vu','54','xy','26','vt','a0','yw','w4','ww','2w','02','uy','yy','65','1u','2w','4x','9a','8w','4x','4z','06','8u','uw','5v','x5','vy','2z','15','58','28','ux','62','ay','68','s5','v5','62','0w','yy','x4','zw','9w','23','13','56','u6','z2','11','51','74','t9','9t','7a','45','s4','3y','1v','3y','r5','3r','2w','wu','y3','u6','43','55','z3','yz','1w','45','xx','96','9w','u8','t3','z5','2x','u2','sw','yw','z6','65','v0','ys','07','zx','43','9x','76','v6','u8','63','84','95','3y','zy','66','43','w6','2y','65','4y','41','v0','15','5z','2z','yv','24','7v','31','6u','96','6x','v5','72','59','68','yv','45','4v','vy','v2','vx','61','2y','z9','vt','1y','86','39','90','x9','1v','s1','w5','58','66','sw','zs','7a','6v','yz','3v','7a','34','24','1t','2z','zt','w9','10','4a','92','xy','40','8v','w0','53','4y','b5','2u','0z','51','67','w4','16','9w','18','wv','t4','z0','a2','vw','x1','x2','b2','94','u7','15','c2','z4','wv','56','62','3z','w6','3v','82','0y','s3','wz','2v','xt','uw','wx','x3','96','y0','yy','73','44','wz','w3','54','61','x5','04','av','ww','6a','vy','xv','4u','6w','52','2v','90','45','63','3y','70','wa','x4','62','23','s0','zz','9w','82','36','ux','80','64','z6','91','37','46','t4','u3','cy','9y','2x','z6','02','u5','5v','vt','9y','95','42','uv','c3','v5','x9','1y','62','97','0z','35','x2','2w','ux','wu','y5','05','wv','8s','29','v3','r5','3v','b4','y3','z4','9x','zx','wv','vw','9t','c4','7z','3y','45','b6','32','x4','93','xx','86','0a','1v','av','93','3a','6z','25','ut','rv','ur','xv','y2','v0','y5','1z','47','vx','0r','5x']

alpha = ['a', 'b', 'c', 'd', 'e', 'f', 'g', 'h', 'i', 'j', 'k', 'l', 'm', 'n', 'o', 'p', 'q', 'r', 's', 't', 'u', 'v', 'w', 'x', 'y', 'z', '0', '1', '2', '3', '4', '5', '6', '7', '8', '9']
alpha2 = ['a', 'b', 'c', 'r', 's', 't', 'u', 'v', 'w', 'x', 'y', 'z', '0', '1', '2', '3', '4', '5', '6', '7', '8', '9']
alpha3 = ['a', 'b', 'c', 'd', 'e', 'f', 'g', 'h', 'i', 'k', 'l', 'm', 'n', '1', '2', '3', '4', '5', '6', '7', '8', '9']
```


```python
def cshift(c, n, rev=False, alphabet=alpha):
    nval = alphabet.index(n)
    if rev:
        nval = -nval
    return alphabet[(alphabet.index(c) + nval) % len(alphabet)]

def ashift(n, alphabet=alpha):
    return [cshift(x, n) for x in alphabet]

def vig(ct, key, rev, alphabet):
    r = []
    for i in range(len(ct)):
        r.append(cshift(ct[i], key[i % len(key)], rev, alphabet))
    return ''.join(r)

def vig_ac(ct, key, rev, alphabet):
    r = []
    for i in range(min(len(ct), len(key))):
        r.append(cshift(ct[i], key[i], rev, alphabet))
    j = i + 1
    if rev:
        for i in range(j, len(ct)):
            r.append(cshift(ct[i], r[i - j], rev, alphabet))
    else:
        for i in range(j, len(ct)):
            r.append(cshift(ct[i], ct[i - j], rev, alphabet))
    return ''.join(r)

def envig(ct, key, ac=False, alphabet=alpha):
    if ac:
        return vig_ac(ct, key, False, alphabet)
    return vig(ct, key, False, alphabet)

def devig(ct, key, ac=False, alphabet=alpha):
    if ac:
        return vig_ac(ct, key, True, alphabet)
    return vig(ct, key, True, alphabet)
```


```python
def vsquare(alphabet=alpha):
    s = {}
    for i in alphabet:
        s[i] = ashift(i, alphabet)
    return s
```


```python
def bisquare(alphabet=alpha):
    s = {}
    for i in alphabet:
        s[i] = [j+i for j in alphabet]
    return s
```


```python
pd.DataFrame(vsquare(), index=alpha)
```




<div>
<style scoped>
    .dataframe tbody tr th:only-of-type {
        vertical-align: middle;
    }

    .dataframe tbody tr th {
        vertical-align: top;
    }

    .dataframe thead th {
        text-align: right;
    }
</style>
<table border="1" class="dataframe">
  <thead>
    <tr style="text-align: right;">
      <th></th>
      <th>a</th>
      <th>b</th>
      <th>c</th>
      <th>d</th>
      <th>e</th>
      <th>f</th>
      <th>g</th>
      <th>h</th>
      <th>i</th>
      <th>j</th>
      <th>k</th>
      <th>l</th>
      <th>m</th>
      <th>n</th>
      <th>o</th>
      <th>p</th>
      <th>q</th>
      <th>r</th>
      <th>s</th>
      <th>t</th>
      <th>u</th>
      <th>v</th>
      <th>w</th>
      <th>x</th>
      <th>y</th>
      <th>z</th>
      <th>0</th>
      <th>1</th>
      <th>2</th>
      <th>3</th>
      <th>4</th>
      <th>5</th>
      <th>6</th>
      <th>7</th>
      <th>8</th>
      <th>9</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th>a</th>
      <td>a</td>
      <td>b</td>
      <td>c</td>
      <td>d</td>
      <td>e</td>
      <td>f</td>
      <td>g</td>
      <td>h</td>
      <td>i</td>
      <td>j</td>
      <td>k</td>
      <td>l</td>
      <td>m</td>
      <td>n</td>
      <td>o</td>
      <td>p</td>
      <td>q</td>
      <td>r</td>
      <td>s</td>
      <td>t</td>
      <td>u</td>
      <td>v</td>
      <td>w</td>
      <td>x</td>
      <td>y</td>
      <td>z</td>
      <td>0</td>
      <td>1</td>
      <td>2</td>
      <td>3</td>
      <td>4</td>
      <td>5</td>
      <td>6</td>
      <td>7</td>
      <td>8</td>
      <td>9</td>
    </tr>
    <tr>
      <th>b</th>
      <td>b</td>
      <td>c</td>
      <td>d</td>
      <td>e</td>
      <td>f</td>
      <td>g</td>
      <td>h</td>
      <td>i</td>
      <td>j</td>
      <td>k</td>
      <td>l</td>
      <td>m</td>
      <td>n</td>
      <td>o</td>
      <td>p</td>
      <td>q</td>
      <td>r</td>
      <td>s</td>
      <td>t</td>
      <td>u</td>
      <td>v</td>
      <td>w</td>
      <td>x</td>
      <td>y</td>
      <td>z</td>
      <td>0</td>
      <td>1</td>
      <td>2</td>
      <td>3</td>
      <td>4</td>
      <td>5</td>
      <td>6</td>
      <td>7</td>
      <td>8</td>
      <td>9</td>
      <td>a</td>
    </tr>
    <tr>
      <th>c</th>
      <td>c</td>
      <td>d</td>
      <td>e</td>
      <td>f</td>
      <td>g</td>
      <td>h</td>
      <td>i</td>
      <td>j</td>
      <td>k</td>
      <td>l</td>
      <td>m</td>
      <td>n</td>
      <td>o</td>
      <td>p</td>
      <td>q</td>
      <td>r</td>
      <td>s</td>
      <td>t</td>
      <td>u</td>
      <td>v</td>
      <td>w</td>
      <td>x</td>
      <td>y</td>
      <td>z</td>
      <td>0</td>
      <td>1</td>
      <td>2</td>
      <td>3</td>
      <td>4</td>
      <td>5</td>
      <td>6</td>
      <td>7</td>
      <td>8</td>
      <td>9</td>
      <td>a</td>
      <td>b</td>
    </tr>
    <tr>
      <th>d</th>
      <td>d</td>
      <td>e</td>
      <td>f</td>
      <td>g</td>
      <td>h</td>
      <td>i</td>
      <td>j</td>
      <td>k</td>
      <td>l</td>
      <td>m</td>
      <td>n</td>
      <td>o</td>
      <td>p</td>
      <td>q</td>
      <td>r</td>
      <td>s</td>
      <td>t</td>
      <td>u</td>
      <td>v</td>
      <td>w</td>
      <td>x</td>
      <td>y</td>
      <td>z</td>
      <td>0</td>
      <td>1</td>
      <td>2</td>
      <td>3</td>
      <td>4</td>
      <td>5</td>
      <td>6</td>
      <td>7</td>
      <td>8</td>
      <td>9</td>
      <td>a</td>
      <td>b</td>
      <td>c</td>
    </tr>
    <tr>
      <th>e</th>
      <td>e</td>
      <td>f</td>
      <td>g</td>
      <td>h</td>
      <td>i</td>
      <td>j</td>
      <td>k</td>
      <td>l</td>
      <td>m</td>
      <td>n</td>
      <td>o</td>
      <td>p</td>
      <td>q</td>
      <td>r</td>
      <td>s</td>
      <td>t</td>
      <td>u</td>
      <td>v</td>
      <td>w</td>
      <td>x</td>
      <td>y</td>
      <td>z</td>
      <td>0</td>
      <td>1</td>
      <td>2</td>
      <td>3</td>
      <td>4</td>
      <td>5</td>
      <td>6</td>
      <td>7</td>
      <td>8</td>
      <td>9</td>
      <td>a</td>
      <td>b</td>
      <td>c</td>
      <td>d</td>
    </tr>
    <tr>
      <th>f</th>
      <td>f</td>
      <td>g</td>
      <td>h</td>
      <td>i</td>
      <td>j</td>
      <td>k</td>
      <td>l</td>
      <td>m</td>
      <td>n</td>
      <td>o</td>
      <td>p</td>
      <td>q</td>
      <td>r</td>
      <td>s</td>
      <td>t</td>
      <td>u</td>
      <td>v</td>
      <td>w</td>
      <td>x</td>
      <td>y</td>
      <td>z</td>
      <td>0</td>
      <td>1</td>
      <td>2</td>
      <td>3</td>
      <td>4</td>
      <td>5</td>
      <td>6</td>
      <td>7</td>
      <td>8</td>
      <td>9</td>
      <td>a</td>
      <td>b</td>
      <td>c</td>
      <td>d</td>
      <td>e</td>
    </tr>
    <tr>
      <th>g</th>
      <td>g</td>
      <td>h</td>
      <td>i</td>
      <td>j</td>
      <td>k</td>
      <td>l</td>
      <td>m</td>
      <td>n</td>
      <td>o</td>
      <td>p</td>
      <td>q</td>
      <td>r</td>
      <td>s</td>
      <td>t</td>
      <td>u</td>
      <td>v</td>
      <td>w</td>
      <td>x</td>
      <td>y</td>
      <td>z</td>
      <td>0</td>
      <td>1</td>
      <td>2</td>
      <td>3</td>
      <td>4</td>
      <td>5</td>
      <td>6</td>
      <td>7</td>
      <td>8</td>
      <td>9</td>
      <td>a</td>
      <td>b</td>
      <td>c</td>
      <td>d</td>
      <td>e</td>
      <td>f</td>
    </tr>
    <tr>
      <th>h</th>
      <td>h</td>
      <td>i</td>
      <td>j</td>
      <td>k</td>
      <td>l</td>
      <td>m</td>
      <td>n</td>
      <td>o</td>
      <td>p</td>
      <td>q</td>
      <td>r</td>
      <td>s</td>
      <td>t</td>
      <td>u</td>
      <td>v</td>
      <td>w</td>
      <td>x</td>
      <td>y</td>
      <td>z</td>
      <td>0</td>
      <td>1</td>
      <td>2</td>
      <td>3</td>
      <td>4</td>
      <td>5</td>
      <td>6</td>
      <td>7</td>
      <td>8</td>
      <td>9</td>
      <td>a</td>
      <td>b</td>
      <td>c</td>
      <td>d</td>
      <td>e</td>
      <td>f</td>
      <td>g</td>
    </tr>
    <tr>
      <th>i</th>
      <td>i</td>
      <td>j</td>
      <td>k</td>
      <td>l</td>
      <td>m</td>
      <td>n</td>
      <td>o</td>
      <td>p</td>
      <td>q</td>
      <td>r</td>
      <td>s</td>
      <td>t</td>
      <td>u</td>
      <td>v</td>
      <td>w</td>
      <td>x</td>
      <td>y</td>
      <td>z</td>
      <td>0</td>
      <td>1</td>
      <td>2</td>
      <td>3</td>
      <td>4</td>
      <td>5</td>
      <td>6</td>
      <td>7</td>
      <td>8</td>
      <td>9</td>
      <td>a</td>
      <td>b</td>
      <td>c</td>
      <td>d</td>
      <td>e</td>
      <td>f</td>
      <td>g</td>
      <td>h</td>
    </tr>
    <tr>
      <th>j</th>
      <td>j</td>
      <td>k</td>
      <td>l</td>
      <td>m</td>
      <td>n</td>
      <td>o</td>
      <td>p</td>
      <td>q</td>
      <td>r</td>
      <td>s</td>
      <td>t</td>
      <td>u</td>
      <td>v</td>
      <td>w</td>
      <td>x</td>
      <td>y</td>
      <td>z</td>
      <td>0</td>
      <td>1</td>
      <td>2</td>
      <td>3</td>
      <td>4</td>
      <td>5</td>
      <td>6</td>
      <td>7</td>
      <td>8</td>
      <td>9</td>
      <td>a</td>
      <td>b</td>
      <td>c</td>
      <td>d</td>
      <td>e</td>
      <td>f</td>
      <td>g</td>
      <td>h</td>
      <td>i</td>
    </tr>
    <tr>
      <th>k</th>
      <td>k</td>
      <td>l</td>
      <td>m</td>
      <td>n</td>
      <td>o</td>
      <td>p</td>
      <td>q</td>
      <td>r</td>
      <td>s</td>
      <td>t</td>
      <td>u</td>
      <td>v</td>
      <td>w</td>
      <td>x</td>
      <td>y</td>
      <td>z</td>
      <td>0</td>
      <td>1</td>
      <td>2</td>
      <td>3</td>
      <td>4</td>
      <td>5</td>
      <td>6</td>
      <td>7</td>
      <td>8</td>
      <td>9</td>
      <td>a</td>
      <td>b</td>
      <td>c</td>
      <td>d</td>
      <td>e</td>
      <td>f</td>
      <td>g</td>
      <td>h</td>
      <td>i</td>
      <td>j</td>
    </tr>
    <tr>
      <th>l</th>
      <td>l</td>
      <td>m</td>
      <td>n</td>
      <td>o</td>
      <td>p</td>
      <td>q</td>
      <td>r</td>
      <td>s</td>
      <td>t</td>
      <td>u</td>
      <td>v</td>
      <td>w</td>
      <td>x</td>
      <td>y</td>
      <td>z</td>
      <td>0</td>
      <td>1</td>
      <td>2</td>
      <td>3</td>
      <td>4</td>
      <td>5</td>
      <td>6</td>
      <td>7</td>
      <td>8</td>
      <td>9</td>
      <td>a</td>
      <td>b</td>
      <td>c</td>
      <td>d</td>
      <td>e</td>
      <td>f</td>
      <td>g</td>
      <td>h</td>
      <td>i</td>
      <td>j</td>
      <td>k</td>
    </tr>
    <tr>
      <th>m</th>
      <td>m</td>
      <td>n</td>
      <td>o</td>
      <td>p</td>
      <td>q</td>
      <td>r</td>
      <td>s</td>
      <td>t</td>
      <td>u</td>
      <td>v</td>
      <td>w</td>
      <td>x</td>
      <td>y</td>
      <td>z</td>
      <td>0</td>
      <td>1</td>
      <td>2</td>
      <td>3</td>
      <td>4</td>
      <td>5</td>
      <td>6</td>
      <td>7</td>
      <td>8</td>
      <td>9</td>
      <td>a</td>
      <td>b</td>
      <td>c</td>
      <td>d</td>
      <td>e</td>
      <td>f</td>
      <td>g</td>
      <td>h</td>
      <td>i</td>
      <td>j</td>
      <td>k</td>
      <td>l</td>
    </tr>
    <tr>
      <th>n</th>
      <td>n</td>
      <td>o</td>
      <td>p</td>
      <td>q</td>
      <td>r</td>
      <td>s</td>
      <td>t</td>
      <td>u</td>
      <td>v</td>
      <td>w</td>
      <td>x</td>
      <td>y</td>
      <td>z</td>
      <td>0</td>
      <td>1</td>
      <td>2</td>
      <td>3</td>
      <td>4</td>
      <td>5</td>
      <td>6</td>
      <td>7</td>
      <td>8</td>
      <td>9</td>
      <td>a</td>
      <td>b</td>
      <td>c</td>
      <td>d</td>
      <td>e</td>
      <td>f</td>
      <td>g</td>
      <td>h</td>
      <td>i</td>
      <td>j</td>
      <td>k</td>
      <td>l</td>
      <td>m</td>
    </tr>
    <tr>
      <th>o</th>
      <td>o</td>
      <td>p</td>
      <td>q</td>
      <td>r</td>
      <td>s</td>
      <td>t</td>
      <td>u</td>
      <td>v</td>
      <td>w</td>
      <td>x</td>
      <td>y</td>
      <td>z</td>
      <td>0</td>
      <td>1</td>
      <td>2</td>
      <td>3</td>
      <td>4</td>
      <td>5</td>
      <td>6</td>
      <td>7</td>
      <td>8</td>
      <td>9</td>
      <td>a</td>
      <td>b</td>
      <td>c</td>
      <td>d</td>
      <td>e</td>
      <td>f</td>
      <td>g</td>
      <td>h</td>
      <td>i</td>
      <td>j</td>
      <td>k</td>
      <td>l</td>
      <td>m</td>
      <td>n</td>
    </tr>
    <tr>
      <th>p</th>
      <td>p</td>
      <td>q</td>
      <td>r</td>
      <td>s</td>
      <td>t</td>
      <td>u</td>
      <td>v</td>
      <td>w</td>
      <td>x</td>
      <td>y</td>
      <td>z</td>
      <td>0</td>
      <td>1</td>
      <td>2</td>
      <td>3</td>
      <td>4</td>
      <td>5</td>
      <td>6</td>
      <td>7</td>
      <td>8</td>
      <td>9</td>
      <td>a</td>
      <td>b</td>
      <td>c</td>
      <td>d</td>
      <td>e</td>
      <td>f</td>
      <td>g</td>
      <td>h</td>
      <td>i</td>
      <td>j</td>
      <td>k</td>
      <td>l</td>
      <td>m</td>
      <td>n</td>
      <td>o</td>
    </tr>
    <tr>
      <th>q</th>
      <td>q</td>
      <td>r</td>
      <td>s</td>
      <td>t</td>
      <td>u</td>
      <td>v</td>
      <td>w</td>
      <td>x</td>
      <td>y</td>
      <td>z</td>
      <td>0</td>
      <td>1</td>
      <td>2</td>
      <td>3</td>
      <td>4</td>
      <td>5</td>
      <td>6</td>
      <td>7</td>
      <td>8</td>
      <td>9</td>
      <td>a</td>
      <td>b</td>
      <td>c</td>
      <td>d</td>
      <td>e</td>
      <td>f</td>
      <td>g</td>
      <td>h</td>
      <td>i</td>
      <td>j</td>
      <td>k</td>
      <td>l</td>
      <td>m</td>
      <td>n</td>
      <td>o</td>
      <td>p</td>
    </tr>
    <tr>
      <th>r</th>
      <td>r</td>
      <td>s</td>
      <td>t</td>
      <td>u</td>
      <td>v</td>
      <td>w</td>
      <td>x</td>
      <td>y</td>
      <td>z</td>
      <td>0</td>
      <td>1</td>
      <td>2</td>
      <td>3</td>
      <td>4</td>
      <td>5</td>
      <td>6</td>
      <td>7</td>
      <td>8</td>
      <td>9</td>
      <td>a</td>
      <td>b</td>
      <td>c</td>
      <td>d</td>
      <td>e</td>
      <td>f</td>
      <td>g</td>
      <td>h</td>
      <td>i</td>
      <td>j</td>
      <td>k</td>
      <td>l</td>
      <td>m</td>
      <td>n</td>
      <td>o</td>
      <td>p</td>
      <td>q</td>
    </tr>
    <tr>
      <th>s</th>
      <td>s</td>
      <td>t</td>
      <td>u</td>
      <td>v</td>
      <td>w</td>
      <td>x</td>
      <td>y</td>
      <td>z</td>
      <td>0</td>
      <td>1</td>
      <td>2</td>
      <td>3</td>
      <td>4</td>
      <td>5</td>
      <td>6</td>
      <td>7</td>
      <td>8</td>
      <td>9</td>
      <td>a</td>
      <td>b</td>
      <td>c</td>
      <td>d</td>
      <td>e</td>
      <td>f</td>
      <td>g</td>
      <td>h</td>
      <td>i</td>
      <td>j</td>
      <td>k</td>
      <td>l</td>
      <td>m</td>
      <td>n</td>
      <td>o</td>
      <td>p</td>
      <td>q</td>
      <td>r</td>
    </tr>
    <tr>
      <th>t</th>
      <td>t</td>
      <td>u</td>
      <td>v</td>
      <td>w</td>
      <td>x</td>
      <td>y</td>
      <td>z</td>
      <td>0</td>
      <td>1</td>
      <td>2</td>
      <td>3</td>
      <td>4</td>
      <td>5</td>
      <td>6</td>
      <td>7</td>
      <td>8</td>
      <td>9</td>
      <td>a</td>
      <td>b</td>
      <td>c</td>
      <td>d</td>
      <td>e</td>
      <td>f</td>
      <td>g</td>
      <td>h</td>
      <td>i</td>
      <td>j</td>
      <td>k</td>
      <td>l</td>
      <td>m</td>
      <td>n</td>
      <td>o</td>
      <td>p</td>
      <td>q</td>
      <td>r</td>
      <td>s</td>
    </tr>
    <tr>
      <th>u</th>
      <td>u</td>
      <td>v</td>
      <td>w</td>
      <td>x</td>
      <td>y</td>
      <td>z</td>
      <td>0</td>
      <td>1</td>
      <td>2</td>
      <td>3</td>
      <td>4</td>
      <td>5</td>
      <td>6</td>
      <td>7</td>
      <td>8</td>
      <td>9</td>
      <td>a</td>
      <td>b</td>
      <td>c</td>
      <td>d</td>
      <td>e</td>
      <td>f</td>
      <td>g</td>
      <td>h</td>
      <td>i</td>
      <td>j</td>
      <td>k</td>
      <td>l</td>
      <td>m</td>
      <td>n</td>
      <td>o</td>
      <td>p</td>
      <td>q</td>
      <td>r</td>
      <td>s</td>
      <td>t</td>
    </tr>
    <tr>
      <th>v</th>
      <td>v</td>
      <td>w</td>
      <td>x</td>
      <td>y</td>
      <td>z</td>
      <td>0</td>
      <td>1</td>
      <td>2</td>
      <td>3</td>
      <td>4</td>
      <td>5</td>
      <td>6</td>
      <td>7</td>
      <td>8</td>
      <td>9</td>
      <td>a</td>
      <td>b</td>
      <td>c</td>
      <td>d</td>
      <td>e</td>
      <td>f</td>
      <td>g</td>
      <td>h</td>
      <td>i</td>
      <td>j</td>
      <td>k</td>
      <td>l</td>
      <td>m</td>
      <td>n</td>
      <td>o</td>
      <td>p</td>
      <td>q</td>
      <td>r</td>
      <td>s</td>
      <td>t</td>
      <td>u</td>
    </tr>
    <tr>
      <th>w</th>
      <td>w</td>
      <td>x</td>
      <td>y</td>
      <td>z</td>
      <td>0</td>
      <td>1</td>
      <td>2</td>
      <td>3</td>
      <td>4</td>
      <td>5</td>
      <td>6</td>
      <td>7</td>
      <td>8</td>
      <td>9</td>
      <td>a</td>
      <td>b</td>
      <td>c</td>
      <td>d</td>
      <td>e</td>
      <td>f</td>
      <td>g</td>
      <td>h</td>
      <td>i</td>
      <td>j</td>
      <td>k</td>
      <td>l</td>
      <td>m</td>
      <td>n</td>
      <td>o</td>
      <td>p</td>
      <td>q</td>
      <td>r</td>
      <td>s</td>
      <td>t</td>
      <td>u</td>
      <td>v</td>
    </tr>
    <tr>
      <th>x</th>
      <td>x</td>
      <td>y</td>
      <td>z</td>
      <td>0</td>
      <td>1</td>
      <td>2</td>
      <td>3</td>
      <td>4</td>
      <td>5</td>
      <td>6</td>
      <td>7</td>
      <td>8</td>
      <td>9</td>
      <td>a</td>
      <td>b</td>
      <td>c</td>
      <td>d</td>
      <td>e</td>
      <td>f</td>
      <td>g</td>
      <td>h</td>
      <td>i</td>
      <td>j</td>
      <td>k</td>
      <td>l</td>
      <td>m</td>
      <td>n</td>
      <td>o</td>
      <td>p</td>
      <td>q</td>
      <td>r</td>
      <td>s</td>
      <td>t</td>
      <td>u</td>
      <td>v</td>
      <td>w</td>
    </tr>
    <tr>
      <th>y</th>
      <td>y</td>
      <td>z</td>
      <td>0</td>
      <td>1</td>
      <td>2</td>
      <td>3</td>
      <td>4</td>
      <td>5</td>
      <td>6</td>
      <td>7</td>
      <td>8</td>
      <td>9</td>
      <td>a</td>
      <td>b</td>
      <td>c</td>
      <td>d</td>
      <td>e</td>
      <td>f</td>
      <td>g</td>
      <td>h</td>
      <td>i</td>
      <td>j</td>
      <td>k</td>
      <td>l</td>
      <td>m</td>
      <td>n</td>
      <td>o</td>
      <td>p</td>
      <td>q</td>
      <td>r</td>
      <td>s</td>
      <td>t</td>
      <td>u</td>
      <td>v</td>
      <td>w</td>
      <td>x</td>
    </tr>
    <tr>
      <th>z</th>
      <td>z</td>
      <td>0</td>
      <td>1</td>
      <td>2</td>
      <td>3</td>
      <td>4</td>
      <td>5</td>
      <td>6</td>
      <td>7</td>
      <td>8</td>
      <td>9</td>
      <td>a</td>
      <td>b</td>
      <td>c</td>
      <td>d</td>
      <td>e</td>
      <td>f</td>
      <td>g</td>
      <td>h</td>
      <td>i</td>
      <td>j</td>
      <td>k</td>
      <td>l</td>
      <td>m</td>
      <td>n</td>
      <td>o</td>
      <td>p</td>
      <td>q</td>
      <td>r</td>
      <td>s</td>
      <td>t</td>
      <td>u</td>
      <td>v</td>
      <td>w</td>
      <td>x</td>
      <td>y</td>
    </tr>
    <tr>
      <th>0</th>
      <td>0</td>
      <td>1</td>
      <td>2</td>
      <td>3</td>
      <td>4</td>
      <td>5</td>
      <td>6</td>
      <td>7</td>
      <td>8</td>
      <td>9</td>
      <td>a</td>
      <td>b</td>
      <td>c</td>
      <td>d</td>
      <td>e</td>
      <td>f</td>
      <td>g</td>
      <td>h</td>
      <td>i</td>
      <td>j</td>
      <td>k</td>
      <td>l</td>
      <td>m</td>
      <td>n</td>
      <td>o</td>
      <td>p</td>
      <td>q</td>
      <td>r</td>
      <td>s</td>
      <td>t</td>
      <td>u</td>
      <td>v</td>
      <td>w</td>
      <td>x</td>
      <td>y</td>
      <td>z</td>
    </tr>
    <tr>
      <th>1</th>
      <td>1</td>
      <td>2</td>
      <td>3</td>
      <td>4</td>
      <td>5</td>
      <td>6</td>
      <td>7</td>
      <td>8</td>
      <td>9</td>
      <td>a</td>
      <td>b</td>
      <td>c</td>
      <td>d</td>
      <td>e</td>
      <td>f</td>
      <td>g</td>
      <td>h</td>
      <td>i</td>
      <td>j</td>
      <td>k</td>
      <td>l</td>
      <td>m</td>
      <td>n</td>
      <td>o</td>
      <td>p</td>
      <td>q</td>
      <td>r</td>
      <td>s</td>
      <td>t</td>
      <td>u</td>
      <td>v</td>
      <td>w</td>
      <td>x</td>
      <td>y</td>
      <td>z</td>
      <td>0</td>
    </tr>
    <tr>
      <th>2</th>
      <td>2</td>
      <td>3</td>
      <td>4</td>
      <td>5</td>
      <td>6</td>
      <td>7</td>
      <td>8</td>
      <td>9</td>
      <td>a</td>
      <td>b</td>
      <td>c</td>
      <td>d</td>
      <td>e</td>
      <td>f</td>
      <td>g</td>
      <td>h</td>
      <td>i</td>
      <td>j</td>
      <td>k</td>
      <td>l</td>
      <td>m</td>
      <td>n</td>
      <td>o</td>
      <td>p</td>
      <td>q</td>
      <td>r</td>
      <td>s</td>
      <td>t</td>
      <td>u</td>
      <td>v</td>
      <td>w</td>
      <td>x</td>
      <td>y</td>
      <td>z</td>
      <td>0</td>
      <td>1</td>
    </tr>
    <tr>
      <th>3</th>
      <td>3</td>
      <td>4</td>
      <td>5</td>
      <td>6</td>
      <td>7</td>
      <td>8</td>
      <td>9</td>
      <td>a</td>
      <td>b</td>
      <td>c</td>
      <td>d</td>
      <td>e</td>
      <td>f</td>
      <td>g</td>
      <td>h</td>
      <td>i</td>
      <td>j</td>
      <td>k</td>
      <td>l</td>
      <td>m</td>
      <td>n</td>
      <td>o</td>
      <td>p</td>
      <td>q</td>
      <td>r</td>
      <td>s</td>
      <td>t</td>
      <td>u</td>
      <td>v</td>
      <td>w</td>
      <td>x</td>
      <td>y</td>
      <td>z</td>
      <td>0</td>
      <td>1</td>
      <td>2</td>
    </tr>
    <tr>
      <th>4</th>
      <td>4</td>
      <td>5</td>
      <td>6</td>
      <td>7</td>
      <td>8</td>
      <td>9</td>
      <td>a</td>
      <td>b</td>
      <td>c</td>
      <td>d</td>
      <td>e</td>
      <td>f</td>
      <td>g</td>
      <td>h</td>
      <td>i</td>
      <td>j</td>
      <td>k</td>
      <td>l</td>
      <td>m</td>
      <td>n</td>
      <td>o</td>
      <td>p</td>
      <td>q</td>
      <td>r</td>
      <td>s</td>
      <td>t</td>
      <td>u</td>
      <td>v</td>
      <td>w</td>
      <td>x</td>
      <td>y</td>
      <td>z</td>
      <td>0</td>
      <td>1</td>
      <td>2</td>
      <td>3</td>
    </tr>
    <tr>
      <th>5</th>
      <td>5</td>
      <td>6</td>
      <td>7</td>
      <td>8</td>
      <td>9</td>
      <td>a</td>
      <td>b</td>
      <td>c</td>
      <td>d</td>
      <td>e</td>
      <td>f</td>
      <td>g</td>
      <td>h</td>
      <td>i</td>
      <td>j</td>
      <td>k</td>
      <td>l</td>
      <td>m</td>
      <td>n</td>
      <td>o</td>
      <td>p</td>
      <td>q</td>
      <td>r</td>
      <td>s</td>
      <td>t</td>
      <td>u</td>
      <td>v</td>
      <td>w</td>
      <td>x</td>
      <td>y</td>
      <td>z</td>
      <td>0</td>
      <td>1</td>
      <td>2</td>
      <td>3</td>
      <td>4</td>
    </tr>
    <tr>
      <th>6</th>
      <td>6</td>
      <td>7</td>
      <td>8</td>
      <td>9</td>
      <td>a</td>
      <td>b</td>
      <td>c</td>
      <td>d</td>
      <td>e</td>
      <td>f</td>
      <td>g</td>
      <td>h</td>
      <td>i</td>
      <td>j</td>
      <td>k</td>
      <td>l</td>
      <td>m</td>
      <td>n</td>
      <td>o</td>
      <td>p</td>
      <td>q</td>
      <td>r</td>
      <td>s</td>
      <td>t</td>
      <td>u</td>
      <td>v</td>
      <td>w</td>
      <td>x</td>
      <td>y</td>
      <td>z</td>
      <td>0</td>
      <td>1</td>
      <td>2</td>
      <td>3</td>
      <td>4</td>
      <td>5</td>
    </tr>
    <tr>
      <th>7</th>
      <td>7</td>
      <td>8</td>
      <td>9</td>
      <td>a</td>
      <td>b</td>
      <td>c</td>
      <td>d</td>
      <td>e</td>
      <td>f</td>
      <td>g</td>
      <td>h</td>
      <td>i</td>
      <td>j</td>
      <td>k</td>
      <td>l</td>
      <td>m</td>
      <td>n</td>
      <td>o</td>
      <td>p</td>
      <td>q</td>
      <td>r</td>
      <td>s</td>
      <td>t</td>
      <td>u</td>
      <td>v</td>
      <td>w</td>
      <td>x</td>
      <td>y</td>
      <td>z</td>
      <td>0</td>
      <td>1</td>
      <td>2</td>
      <td>3</td>
      <td>4</td>
      <td>5</td>
      <td>6</td>
    </tr>
    <tr>
      <th>8</th>
      <td>8</td>
      <td>9</td>
      <td>a</td>
      <td>b</td>
      <td>c</td>
      <td>d</td>
      <td>e</td>
      <td>f</td>
      <td>g</td>
      <td>h</td>
      <td>i</td>
      <td>j</td>
      <td>k</td>
      <td>l</td>
      <td>m</td>
      <td>n</td>
      <td>o</td>
      <td>p</td>
      <td>q</td>
      <td>r</td>
      <td>s</td>
      <td>t</td>
      <td>u</td>
      <td>v</td>
      <td>w</td>
      <td>x</td>
      <td>y</td>
      <td>z</td>
      <td>0</td>
      <td>1</td>
      <td>2</td>
      <td>3</td>
      <td>4</td>
      <td>5</td>
      <td>6</td>
      <td>7</td>
    </tr>
    <tr>
      <th>9</th>
      <td>9</td>
      <td>a</td>
      <td>b</td>
      <td>c</td>
      <td>d</td>
      <td>e</td>
      <td>f</td>
      <td>g</td>
      <td>h</td>
      <td>i</td>
      <td>j</td>
      <td>k</td>
      <td>l</td>
      <td>m</td>
      <td>n</td>
      <td>o</td>
      <td>p</td>
      <td>q</td>
      <td>r</td>
      <td>s</td>
      <td>t</td>
      <td>u</td>
      <td>v</td>
      <td>w</td>
      <td>x</td>
      <td>y</td>
      <td>z</td>
      <td>0</td>
      <td>1</td>
      <td>2</td>
      <td>3</td>
      <td>4</td>
      <td>5</td>
      <td>6</td>
      <td>7</td>
      <td>8</td>
    </tr>
  </tbody>
</table>
</div>




```python
pd.DataFrame(vsquare(alpha2), index=alpha2)
```




<div>
<style scoped>
    .dataframe tbody tr th:only-of-type {
        vertical-align: middle;
    }

    .dataframe tbody tr th {
        vertical-align: top;
    }

    .dataframe thead th {
        text-align: right;
    }
</style>
<table border="1" class="dataframe">
  <thead>
    <tr style="text-align: right;">
      <th></th>
      <th>a</th>
      <th>b</th>
      <th>c</th>
      <th>r</th>
      <th>s</th>
      <th>t</th>
      <th>u</th>
      <th>v</th>
      <th>w</th>
      <th>x</th>
      <th>y</th>
      <th>z</th>
      <th>0</th>
      <th>1</th>
      <th>2</th>
      <th>3</th>
      <th>4</th>
      <th>5</th>
      <th>6</th>
      <th>7</th>
      <th>8</th>
      <th>9</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th>a</th>
      <td>a</td>
      <td>b</td>
      <td>c</td>
      <td>r</td>
      <td>s</td>
      <td>t</td>
      <td>u</td>
      <td>v</td>
      <td>w</td>
      <td>x</td>
      <td>y</td>
      <td>z</td>
      <td>0</td>
      <td>1</td>
      <td>2</td>
      <td>3</td>
      <td>4</td>
      <td>5</td>
      <td>6</td>
      <td>7</td>
      <td>8</td>
      <td>9</td>
    </tr>
    <tr>
      <th>b</th>
      <td>b</td>
      <td>c</td>
      <td>d</td>
      <td>s</td>
      <td>t</td>
      <td>u</td>
      <td>v</td>
      <td>w</td>
      <td>x</td>
      <td>y</td>
      <td>z</td>
      <td>0</td>
      <td>1</td>
      <td>2</td>
      <td>3</td>
      <td>4</td>
      <td>5</td>
      <td>6</td>
      <td>7</td>
      <td>8</td>
      <td>9</td>
      <td>a</td>
    </tr>
    <tr>
      <th>c</th>
      <td>c</td>
      <td>d</td>
      <td>e</td>
      <td>t</td>
      <td>u</td>
      <td>v</td>
      <td>w</td>
      <td>x</td>
      <td>y</td>
      <td>z</td>
      <td>0</td>
      <td>1</td>
      <td>2</td>
      <td>3</td>
      <td>4</td>
      <td>5</td>
      <td>6</td>
      <td>7</td>
      <td>8</td>
      <td>9</td>
      <td>a</td>
      <td>b</td>
    </tr>
    <tr>
      <th>r</th>
      <td>r</td>
      <td>s</td>
      <td>t</td>
      <td>8</td>
      <td>9</td>
      <td>a</td>
      <td>b</td>
      <td>c</td>
      <td>d</td>
      <td>e</td>
      <td>f</td>
      <td>g</td>
      <td>h</td>
      <td>i</td>
      <td>j</td>
      <td>k</td>
      <td>l</td>
      <td>m</td>
      <td>n</td>
      <td>o</td>
      <td>p</td>
      <td>q</td>
    </tr>
    <tr>
      <th>s</th>
      <td>s</td>
      <td>t</td>
      <td>u</td>
      <td>9</td>
      <td>a</td>
      <td>b</td>
      <td>c</td>
      <td>d</td>
      <td>e</td>
      <td>f</td>
      <td>g</td>
      <td>h</td>
      <td>i</td>
      <td>j</td>
      <td>k</td>
      <td>l</td>
      <td>m</td>
      <td>n</td>
      <td>o</td>
      <td>p</td>
      <td>q</td>
      <td>r</td>
    </tr>
    <tr>
      <th>t</th>
      <td>t</td>
      <td>u</td>
      <td>v</td>
      <td>a</td>
      <td>b</td>
      <td>c</td>
      <td>d</td>
      <td>e</td>
      <td>f</td>
      <td>g</td>
      <td>h</td>
      <td>i</td>
      <td>j</td>
      <td>k</td>
      <td>l</td>
      <td>m</td>
      <td>n</td>
      <td>o</td>
      <td>p</td>
      <td>q</td>
      <td>r</td>
      <td>s</td>
    </tr>
    <tr>
      <th>u</th>
      <td>u</td>
      <td>v</td>
      <td>w</td>
      <td>b</td>
      <td>c</td>
      <td>d</td>
      <td>e</td>
      <td>f</td>
      <td>g</td>
      <td>h</td>
      <td>i</td>
      <td>j</td>
      <td>k</td>
      <td>l</td>
      <td>m</td>
      <td>n</td>
      <td>o</td>
      <td>p</td>
      <td>q</td>
      <td>r</td>
      <td>s</td>
      <td>t</td>
    </tr>
    <tr>
      <th>v</th>
      <td>v</td>
      <td>w</td>
      <td>x</td>
      <td>c</td>
      <td>d</td>
      <td>e</td>
      <td>f</td>
      <td>g</td>
      <td>h</td>
      <td>i</td>
      <td>j</td>
      <td>k</td>
      <td>l</td>
      <td>m</td>
      <td>n</td>
      <td>o</td>
      <td>p</td>
      <td>q</td>
      <td>r</td>
      <td>s</td>
      <td>t</td>
      <td>u</td>
    </tr>
    <tr>
      <th>w</th>
      <td>w</td>
      <td>x</td>
      <td>y</td>
      <td>d</td>
      <td>e</td>
      <td>f</td>
      <td>g</td>
      <td>h</td>
      <td>i</td>
      <td>j</td>
      <td>k</td>
      <td>l</td>
      <td>m</td>
      <td>n</td>
      <td>o</td>
      <td>p</td>
      <td>q</td>
      <td>r</td>
      <td>s</td>
      <td>t</td>
      <td>u</td>
      <td>v</td>
    </tr>
    <tr>
      <th>x</th>
      <td>x</td>
      <td>y</td>
      <td>z</td>
      <td>e</td>
      <td>f</td>
      <td>g</td>
      <td>h</td>
      <td>i</td>
      <td>j</td>
      <td>k</td>
      <td>l</td>
      <td>m</td>
      <td>n</td>
      <td>o</td>
      <td>p</td>
      <td>q</td>
      <td>r</td>
      <td>s</td>
      <td>t</td>
      <td>u</td>
      <td>v</td>
      <td>w</td>
    </tr>
    <tr>
      <th>y</th>
      <td>y</td>
      <td>z</td>
      <td>0</td>
      <td>f</td>
      <td>g</td>
      <td>h</td>
      <td>i</td>
      <td>j</td>
      <td>k</td>
      <td>l</td>
      <td>m</td>
      <td>n</td>
      <td>o</td>
      <td>p</td>
      <td>q</td>
      <td>r</td>
      <td>s</td>
      <td>t</td>
      <td>u</td>
      <td>v</td>
      <td>w</td>
      <td>x</td>
    </tr>
    <tr>
      <th>z</th>
      <td>z</td>
      <td>0</td>
      <td>1</td>
      <td>g</td>
      <td>h</td>
      <td>i</td>
      <td>j</td>
      <td>k</td>
      <td>l</td>
      <td>m</td>
      <td>n</td>
      <td>o</td>
      <td>p</td>
      <td>q</td>
      <td>r</td>
      <td>s</td>
      <td>t</td>
      <td>u</td>
      <td>v</td>
      <td>w</td>
      <td>x</td>
      <td>y</td>
    </tr>
    <tr>
      <th>0</th>
      <td>0</td>
      <td>1</td>
      <td>2</td>
      <td>h</td>
      <td>i</td>
      <td>j</td>
      <td>k</td>
      <td>l</td>
      <td>m</td>
      <td>n</td>
      <td>o</td>
      <td>p</td>
      <td>q</td>
      <td>r</td>
      <td>s</td>
      <td>t</td>
      <td>u</td>
      <td>v</td>
      <td>w</td>
      <td>x</td>
      <td>y</td>
      <td>z</td>
    </tr>
    <tr>
      <th>1</th>
      <td>1</td>
      <td>2</td>
      <td>3</td>
      <td>i</td>
      <td>j</td>
      <td>k</td>
      <td>l</td>
      <td>m</td>
      <td>n</td>
      <td>o</td>
      <td>p</td>
      <td>q</td>
      <td>r</td>
      <td>s</td>
      <td>t</td>
      <td>u</td>
      <td>v</td>
      <td>w</td>
      <td>x</td>
      <td>y</td>
      <td>z</td>
      <td>0</td>
    </tr>
    <tr>
      <th>2</th>
      <td>2</td>
      <td>3</td>
      <td>4</td>
      <td>j</td>
      <td>k</td>
      <td>l</td>
      <td>m</td>
      <td>n</td>
      <td>o</td>
      <td>p</td>
      <td>q</td>
      <td>r</td>
      <td>s</td>
      <td>t</td>
      <td>u</td>
      <td>v</td>
      <td>w</td>
      <td>x</td>
      <td>y</td>
      <td>z</td>
      <td>0</td>
      <td>1</td>
    </tr>
    <tr>
      <th>3</th>
      <td>3</td>
      <td>4</td>
      <td>5</td>
      <td>k</td>
      <td>l</td>
      <td>m</td>
      <td>n</td>
      <td>o</td>
      <td>p</td>
      <td>q</td>
      <td>r</td>
      <td>s</td>
      <td>t</td>
      <td>u</td>
      <td>v</td>
      <td>w</td>
      <td>x</td>
      <td>y</td>
      <td>z</td>
      <td>0</td>
      <td>1</td>
      <td>2</td>
    </tr>
    <tr>
      <th>4</th>
      <td>4</td>
      <td>5</td>
      <td>6</td>
      <td>l</td>
      <td>m</td>
      <td>n</td>
      <td>o</td>
      <td>p</td>
      <td>q</td>
      <td>r</td>
      <td>s</td>
      <td>t</td>
      <td>u</td>
      <td>v</td>
      <td>w</td>
      <td>x</td>
      <td>y</td>
      <td>z</td>
      <td>0</td>
      <td>1</td>
      <td>2</td>
      <td>3</td>
    </tr>
    <tr>
      <th>5</th>
      <td>5</td>
      <td>6</td>
      <td>7</td>
      <td>m</td>
      <td>n</td>
      <td>o</td>
      <td>p</td>
      <td>q</td>
      <td>r</td>
      <td>s</td>
      <td>t</td>
      <td>u</td>
      <td>v</td>
      <td>w</td>
      <td>x</td>
      <td>y</td>
      <td>z</td>
      <td>0</td>
      <td>1</td>
      <td>2</td>
      <td>3</td>
      <td>4</td>
    </tr>
    <tr>
      <th>6</th>
      <td>6</td>
      <td>7</td>
      <td>8</td>
      <td>n</td>
      <td>o</td>
      <td>p</td>
      <td>q</td>
      <td>r</td>
      <td>s</td>
      <td>t</td>
      <td>u</td>
      <td>v</td>
      <td>w</td>
      <td>x</td>
      <td>y</td>
      <td>z</td>
      <td>0</td>
      <td>1</td>
      <td>2</td>
      <td>3</td>
      <td>4</td>
      <td>5</td>
    </tr>
    <tr>
      <th>7</th>
      <td>7</td>
      <td>8</td>
      <td>9</td>
      <td>o</td>
      <td>p</td>
      <td>q</td>
      <td>r</td>
      <td>s</td>
      <td>t</td>
      <td>u</td>
      <td>v</td>
      <td>w</td>
      <td>x</td>
      <td>y</td>
      <td>z</td>
      <td>0</td>
      <td>1</td>
      <td>2</td>
      <td>3</td>
      <td>4</td>
      <td>5</td>
      <td>6</td>
    </tr>
    <tr>
      <th>8</th>
      <td>8</td>
      <td>9</td>
      <td>a</td>
      <td>p</td>
      <td>q</td>
      <td>r</td>
      <td>s</td>
      <td>t</td>
      <td>u</td>
      <td>v</td>
      <td>w</td>
      <td>x</td>
      <td>y</td>
      <td>z</td>
      <td>0</td>
      <td>1</td>
      <td>2</td>
      <td>3</td>
      <td>4</td>
      <td>5</td>
      <td>6</td>
      <td>7</td>
    </tr>
    <tr>
      <th>9</th>
      <td>9</td>
      <td>a</td>
      <td>b</td>
      <td>q</td>
      <td>r</td>
      <td>s</td>
      <td>t</td>
      <td>u</td>
      <td>v</td>
      <td>w</td>
      <td>x</td>
      <td>y</td>
      <td>z</td>
      <td>0</td>
      <td>1</td>
      <td>2</td>
      <td>3</td>
      <td>4</td>
      <td>5</td>
      <td>6</td>
      <td>7</td>
      <td>8</td>
    </tr>
  </tbody>
</table>
</div>




```python
#pd.DataFrame(bisquare(), index=alpha)
```


```python
a='ziumvnnlidcovpkiidc2idcfqfcbivupudcgxqkgrr32yrmgmpsjnjiumqnkwvklxdhgiir20nfrsnnu324zymzmy3zoxoxovrsl9j34bywz610q9ykq9xwh5tts3qifx1pfssyy61xv2qlf910zvugk2wz182npqrwp6sut1omw1trqw0gmbpoo6yusvueozxwupxoszrzp7rxuztsf1mky5wqoqttozlel3hhhyrmr1vqp0zrsmsmr5yru1wwoz4rzvwrucfzdwpewuzsq5trrxyvu1wnc3p0p1sxuxs2rmqgqcurs5zpo7swu7ouytozfpviqvvjw3skmtwsf5nhfxkuvtvppywkqinqstocjpwgrmzvrxyrk1kpgsnsv1hrir6jxsozopuwxlnhopqutkwxf0p1fr3nwop0oamsskxnqzqxowsryxszwtxrnpugl6prnlysvqs3kupsk7x0dteeqxprwqvse2uhpuzrklnmiyrtqovrjrplxkkxsroys5ppfp1woqhmk1mm13mferrdq93ryrfrkx2nso0ngwqhgrsxm3viyzwdgvpy30yqppttqxhqh0ohsuvpiytkqv3rjzrrwxvmkkrnotwpuviggqrzxwgmw2lozuuiow1su0ysi1vvowmzqwvtozlro2oojyutsx0lp0zqqkkslvxryzkpo2uxi7wvixyvkvutsxtknoorouqot3ppvlusmypmxqhxo1op1sziorqmn5kvx7tvx2snqzvjm01vxnoynoqqixmft6upyvsrxziuo0fkqsplloypgbvfq3ljxqrkzujrxmz226vvg5qxjvizt2rwqusuq2mvjkujsvpu21lpkursjp1nqxn1jvjynzrei1trn4upoxwuhtnqc1qz3x02ozsxixtz1t0ytryrojtshsjsq35t1wsmq3lvm2wpualzn0lzh2qs0ogkwtifxu2tq2mvpqi0grvtr6iqqvtsntzvhwyslq02i5vo1ztik1qtzpir2bsmyu3opt3rn7mo0x3tur03jytts5ts1uszsatelwm5fxzrqxmkr5qkc7zmi4n0s03uups4fzlye0kqiosim1lor9urtwsgqsjrw30hyy4nqymmrlvvu1qrsw1ss7zmrmrmkogrqx0snnzk5vsmupmekv1lgxmxw3rsz24rn2xsq1svlwurjwsuq5tqz44jzpjnixqyep42zwmjr32eh7rno7xwkrivr41lutmys6mpw3qxvzhnp2hop33rw4th1ysso0ollnggjq5om0ylpzxsuvi6jiosxnzzzrxwryviov0zhy0v000nn0xpvspqex4wf5qwpy6pypohgtvhq1omo5rtwmhhs6wrz7vr2k40mv23vxdcbiqltq1ihs'
```


```python
def ripple(ct, key, n, fun):
    for i in range(n):
        ct = fun(ct, key)
    return ct
```


```python
ripple(ct, 'de', 64, devig)
```




    't0npj5mul4izg1ixlripfri0p0mxjvnplripfrw0lripfrjqlzirfrinlrxsqyj0wsipfriso3myjvmoqvoxs5w0q2vqkwkqosi1j3lsmvmrgwxrpri2h0qol5sxnrixytipfwnnlriuuru2o6lwirpwsupsotvtv2u2t5t0q2pruzqquyw1s1tpo3jzr0tpm3i3g6pqz4opt4x105p3p1vyy2v0s2wox6xvmsk0z4xuuwjsx2pym1pxw1nxjtjqxur4mxlousnzo4r1u6r4l6o1r5lzixmnx6v0s2vyn2wsisjvt3wuq3t2w6s4mvqtnxqvo2ovy2oym2uts3kyostxt2pymzpvrzvzjrlv05rsrrmwv5r1j5sul4uuftvnp4uxsyuusrp2jzwqq3oxuzwnv6wpn4uuzuxqk2iru1mujvvxu5uwtrvnowxqozmwxwkvftluzylqfwitvxqvlvsts3p0mypuwyp4g5k2ntvrkwxo0zo4qvuuxyuwuwmwxwv3mzuzm3xtnyuu06jqn6jozrtqgso2pzt0i4xn0zn0qvj2m5o4sxn1q5n3qrjnu3lyp5qtxyxpr0o0l6i4u2wpostrjrss06n1i3ttu5q3f4vnx4i4rzuuv6nvj5q2n0ptuzmnpuqzfxrtuvvugxrzv2pxltosm1uwm0low3psitmnxuppswuvqxqznwuptzuwkusslrizh3oym1ptfrlsqtuwisurmur2ryxoo3wwh4oqwzltmxnnttkxm0qzzwitg5iul0x3gxr0usnvt0kyovk4syq1nsqrgvi0puj1swozltxttyloxxput2jql0v2izrzrrsrs2ouz5kwttwqmstyf2myzuk0q1lxuwm0g5uyq1nzq3syutp2j2jyovswjrpqy2upoxqrlus0i4p0owqwr6qom2qtg6ltv6xup5jol2jpfti2wvupurrzquwtm0koq6o0gvqtxrr2f6qoorjyg0npuyi3k3nxptl4g5nqtsupluwvnrjvq1uspwqsp3rvx2i1i1mnpus3rzoussjsprkuq5iyjxu1yzkwgtlntsmzfsvpx6t4i3q2ruirf6iwo3v1izoyouq4psmoq0j1krjrl0sup2tns5m3ksvxn6txgrjrvuups0x0q4xvf5pumxrwn0sswvmpg4mpu0sqkrvrl3wtmxpntzm1nrnxo1x0ruktq3j2g5wuuxxsf1ppnrk1kxptsvp1kzvtl4npfvispvmzn6uxp1jrhzq0s4ixkyr2pzvtiuoup1r4i4swt1o4g6kswzryrytpp1kwp4won3m3h6lxq3ixurjzu2oulxjum6vtm1suszt1kvkzq4p4trk0ltiwsuroryo3i3tzxwpplyouw0swr0iuy3uwo1pnn4q2rynrwtn1h6wqvwvsnrtooulxf6lxpzk0qsl2zyovovwtluswj3tntzmxlvp2lzittyrrwzptnwwzvrvyfxjzmzj1prrqu5msqzszw5qxryr0u2wqf2pvq3qzhwiy0uwzuvuxpsqss0unpttrj1mq0rlvirozx3wsg3xvrywqk1uxzulri6pto6jqjvxnqwi1kvormwo4srmo05uvhsssv2nslsp2owwpmsr2pzmrg5p2ost0u2u2x3vutwjrt6qum5ktxsjtn6rwxztsn3ssl3oyqylzzxrpp0nqnrwshwwql4rsi6u2q5mtqtrnwsk1ttpolys3f2pvo3nup6ivxsjup3sp0ti3gslr0vutl0kxt5pzmxkyytm4o0onn0rqrtiou1owo5v2o3r3s4tpvypxo3iuuxvsr2v0rws2o4xqmzxvg5jzlsl2qwonusktrvows5w3svv0p1j3iywow1qpryqqzxsynwvtz5pqs1rqt1kvn6jsxzowm0vznvjrmsxtutiufuuxo0s4ozssxzntk5vossksu0nnoxvui5pwx3kstrpvo1k3g6qrqxr2rynoxtvxj3snnxq4u2pnv4wtqsxyt0svlrqop6ssk3t0srnpg5xz05wqnttzvtt4qslysvt4j2rqw5mulxs2ytu3ozo0urq4t4nqyurwn0vru5pyj3v0rxm0r2vry6rwhrixtxprt6kpm5xwtsnxxuosltwpw3rthxjnz2uzmujtv3kxr3l1s2u3uuswlyl1t5jqt0luq2jpywmsk0ksqsoyiumuu1pqqsstx6wsstsvo2wqistrl1juqvp1t4q4ituyyuu4g1j1uyosmul0nsxsqzpzt2i2nypxtxv0h5xpv6s1g0ruprruf1rnqskqmzi2szt1nzmvpss1ltx2xsi4hzn1qtiygsmsn2u1jwmoo3ntszxtv2j2i4uzw0x1runuu2szk2quu1susxjwp1tvqvmrq0vrrxuqx2utj1vyt5u4mrs1srjujyjtuxqun5jppuw2r5xwl5prgxk1t4u2gsnov6urmvrrv6r0q0ppqvnpk5pws6xyluswwrkwtzsuz1qqovtxu3k0p2xsp4krh0nwyyjslxlyzyx0i3p10yn0krt2uyrvk2rrwyougzkvqrlpisktlzx2mwmuvzs0kvkzt0uxl1o0yrksu6julrsqustyqrxws1uzruvwk6l0uyqzgwnvxswyr2itwwu0n2xxr3s2h0iz0uxuqtn2oyi1trjpxux1syir0zj1l5puuyx3ovr1lyqsitkqm1o1krwoq5jzf1rrz0mzn0xtntkrjsxp00vvrus1z2ryl0xzltw2o6pryrxzr6uvq1ipfrinlrmyjwm1pvs3jtontt'




```python
k = []
for c in ct:
    ks = ''
    for i in alpha:
        if cshift(c, i, True) not in ['0', '1', '2', '3', '4', '5', '6', '7', '8', '9']:
            ks += i
    k.append(ks)
```


```python
kd = {}
for i in range(1, 65):
    kas = []
    for j in range(i):
        ka = ''
        for a in alpha:
            bad=False
            for b in k[j::i]:
                if a not in b:
                    bad=True
                    break
            if not bad:
                ka += a
        kas.append(ka)
    kd[i] = kas
print(kd)
```

    {1: ['nopqr'], 2: ['nopqr', 'lmnopqr'], 3: ['nopqr', 'nopqr', 'nopqr'], 4: ['nopqr', 'lmnopqrstuv', 'klmnopqrstu', 'jklmnopqr'], 5: ['nopqr', 'nopqr', 'nopqr', 'nopqr', 'mnopqr'], 6: ['nopqr', 'lmnopqr', 'nopqr', 'lmnopqr', 'nopqr', 'lmnopqr'], 7: ['mnopqr', 'mnopqr', 'nopqr', 'nopqr', 'mnopqr', 'nopqr', 'nopqr'], 8: ['nopqrstuvwx', 'lmnopqrstuv', 'klmnopqrstu', 'jklmnopqrst', 'hijklmnopqr', 'lmnopqrstuv', 'klmnopqrstu', 'hijklmnopqr'], 9: ['nopqr', 'nopqr', 'mnopqr', 'nopqr', 'nopqr', 'nopqr', 'nopqr', 'nopqr', 'mnopqr'], 10: ['nopqr', 'lmnopqr', 'nopqr', 'lmnopqr', 'mnopqr', 'lmnopqr', 'nopqr', 'lmnopqr', 'nopqr', 'lmnopqr'], 11: ['nopqr', 'nopqr', 'nopqr', 'nopqr', 'lmnopqr', 'nopqr', 'nopqr', 'nopqr', 'nopqr', 'mnopqr', 'nopqr'], 12: ['nopqr', 'lmnopqrstuv', 'klmnopqrstu', 'jklmnopqr', 'nopqr', 'lmnopqrstuv', 'klmnopqrstu', 'jklmnopqr', 'nopqr', 'lmnopqrstuv', 'klmnopqrstu', 'jklmnopqr'], 13: ['nopqr', 'nopqr', 'nopqr', 'mnopqr', 'nopqr', 'nopqr', 'nopqr', 'nopqr', 'nopqr', 'nopqr', 'nopqr', 'mnopqr', 'mnopqr'], 14: ['mnopqr', 'lmnopqr', 'nopqr', 'lmnopqr', 'mnopqr', 'lmnopqr', 'nopqr', 'lmnopqr', 'mnopqr', 'lmnopqr', 'nopqr', 'lmnopqr', 'nopqr', 'lmnopqr'], 15: ['nopqr', 'nopqr', 'lmnopqr', 'nopqr', 'lmnopqr', 'nopqr', 'nopqr', 'nopqr', 'nopqr', 'mnopqr', 'nopqr', 'mnopqr', 'nopqr', 'nopqr', 'mnopqr'], 16: ['nopqrstuvwx', 'lmnopqrstuv', 'klmnopqrstu', 'jklmnopqrst', 'hijklmnopqr', 'lmnopqrstuv', 'klmnopqrstu', 'hijklmnopqr', 'nopqrstuvwx', 'lmnopqrstuv', 'klmnopqrstu', 'jklmnopqrst', 'hijklmnopqr', 'lmnopqrstuv', 'klmnopqrstu', 'hijklmnopqr'], 17: ['mnopqr', 'nopqr', 'mnopqr', 'nopqr', 'nopqr', 'nopqr', 'lmnopqr', 'mnopqr', 'nopqr', 'nopqr', 'nopqr', 'nopqr', 'mnopqrs', 'nopqr', 'mnopqr', 'nopqr', 'nopqr'], 18: ['nopqr', 'lmnopqr', 'mnopqr', 'lmnopqr', 'nopqr', 'lmnopqr', 'nopqr', 'lmnopqr', 'mnopqr', 'lmnopqr', 'nopqr', 'lmnopqr', 'nopqr', 'lmnopqr', 'nopqr', 'lmnopqr', 'nopqr', 'lmnopqr'], 19: ['nopqr', 'nopqr', 'nopqr', 'mnopqr', 'nopqr', 'lmnopqr', 'lmnopqr', 'mnopqr', 'nopqr', 'nopqr', 'mnopqrs', 'lmnopqr', 'nopqr', 'nopqr', 'lmnopqr', 'nopqr', 'mnopqr', 'mnopqr', 'nopqr'], 20: ['nopqr', 'lmnopqrstuv', 'klmnopqrstu', 'jklmnopqr', 'mnopqr', 'lmnopqrstuv', 'klmnopqrstu', 'jklmnopqr', 'nopqr', 'lmnopqrstuv', 'klmnopqrstu', 'jklmnopqr', 'nopqr', 'lmnopqrstuv', 'klmnopqrstu', 'jklmnopqr', 'nopqr', 'lmnopqrstuv', 'klmnopqrstu', 'jklmnopqr'], 21: ['lmnopqr', 'mnopqr', 'mnopqr', 'nopqr', 'lmnopqr', 'lmnopqr', 'nopqr', 'klmnopqr', 'mnopqr', 'nopqr', 'nopqr', 'mnopqr', 'nopqrs', 'nopqr', 'mnopqr', 'mnopqr', 'nopqr', 'nopqr', 'mnopqr', 'nopqr', 'nopqr'], 22: ['nopqr', 'lmnopqr', 'nopqr', 'lmnopqr', 'klmnopqr', 'lmnopqr', 'nopqr', 'lmnopqr', 'nopqr', 'lmnopqr', 'nopqr', 'klmnopqr', 'nopqr', 'lmnopqr', 'nopqr', 'lmnopqr', 'nopqr', 'lmnopqrs', 'nopqrs', 'lmnopqr', 'mnopqr', 'lmnopqr'], 23: ['nopqr', 'nopqr', 'mnopqr', 'lmnopqr', 'nopqr', 'mnopqr', 'nopqr', 'mnopqr', 'nopqr', 'mnopqr', 'nopqrs', 'nopqr', 'nopqr', 'nopqr', 'mnopqr', 'nopqr', 'mnopqr', 'mnopqr', 'lmnopqr', 'mnopqr', 'mnopqr', 'nopqr', 'nopqr'], 24: ['nopqrstuvwx', 'lmnopqrstuv', 'klmnopqrstu', 'jklmnopqrst', 'hijklmnopqr', 'lmnopqrstuv', 'klmnopqrstu', 'hijklmnopqr', 'nopqrstuvwx', 'lmnopqrstuv', 'klmnopqrstu', 'jklmnopqrst', 'hijklmnopqr', 'lmnopqrstuv', 'klmnopqrstu', 'hijklmnopqr', 'nopqrstuvwx', 'lmnopqrstuv', 'klmnopqrstu', 'jklmnopqrst', 'hijklmnopqr', 'lmnopqrstuv', 'klmnopqrstu', 'hijklmnopqr'], 25: ['mnopqr', 'mnopqr', 'nopqr', 'nopqr', 'lmnopqrs', 'nopqr', 'nopqr', 'nopqr', 'nopqr', 'lmnopqr', 'nopqr', 'nopqr', 'lmnopqr', 'mnopqrs', 'mnopqr', 'mnopqrs', 'mnopqr', 'lmnopqr', 'mnopqr', 'mnopqr', 'mnopqr', 'nopqr', 'lmnopqr', 'mnopqr', 'klmnopqr'], 26: ['nopqr', 'lmnopqr', 'nopqr', 'lmnopqr', 'nopqr', 'lmnopqr', 'nopqrstu', 'lmnopqr', 'nopqr', 'lmnopqr', 'nopqr', 'lmnopqr', 'mnopqr', 'lmnopqrs', 'nopqrs', 'lmnopqr', 'mnopqr', 'lmnopqr', 'nopqr', 'lmnopqr', 'nopqr', 'lmnopqr', 'nopqr', 'lmnopqr', 'mnopqr', 'lmnopqr'], 27: ['mnopqr', 'lmnopqr', 'lmnopqr', 'lmnopqr', 'lmnopqr', 'nopqr', 'lmnopqrs', 'nopqr', 'lmnopqr', 'nopqr', 'nopqr', 'mnopqr', 'nopqr', 'nopqr', 'nopqr', 'nopqrs', 'nopqr', 'mnopqr', 'klmnopqr', 'nopqrs', 'mnopqr', 'lmnopqr', 'lmnopqr', 'mnopqr', 'nopqr', 'nopqr', 'lmnopqr'], 28: ['mnopqr', 'lmnopqrstuv', 'klmnopqrstu', 'jklmnopqr', 'mnopqr', 'lmnopqrstuv', 'klmnopqrstu', 'jklmnopqr', 'mnopqr', 'lmnopqrstuv', 'klmnopqrstu', 'jklmnopqr', 'nopqr', 'lmnopqrstuv', 'klmnopqrstu', 'jklmnopqr', 'nopqr', 'lmnopqrstuv', 'klmnopqrstu', 'jklmnopqr', 'nopqr', 'lmnopqrstuv', 'klmnopqrstu', 'jklmnopqr', 'nopqr', 'lmnopqrstuv', 'klmnopqrstu', 'jklmnopqr'], 29: ['mnopqr', 'nopqr', 'nopqr', 'nopqr', 'lmnopqr', 'nopqr', 'nopqr', 'mnopqr', 'lmnopqr', 'lmnopqr', 'nopqr', 'lmnopqr', 'nopqrs', 'nopqrs', 'mnopqr', 'nopqr', 'lmnopqr', 'nopqr', 'mnopqrs', 'mnopqr', 'nopqr', 'mnopqr', 'lmnopqrs', 'mnopqr', 'mnopqr', 'klmnopqr', 'mnopqr', 'mnopqr', 'nopqr'], 30: ['nopqrs', 'lmnopqr', 'klmnopqr', 'lmnopqrs', 'lmnopqr', 'lmnopqr', 'nopqr', 'lmnopqrs', 'nopqr', 'lmnopqr', 'nopqr', 'lmnopqr', 'nopqr', 'lmnopqr', 'mnopqr', 'lmnopqr', 'nopqr', 'lmnopqr', 'nopqr', 'lmnopqr', 'nopqr', 'lmnopqr', 'nopqr', 'lmnopqr', 'mnopqrs', 'lmnopqr', 'mnopqr', 'lmnopqr', 'nopqrs', 'lmnopqrs'], 31: ['nopqr', 'nopqr', 'nopqr', 'lmnopqr', 'lmnopqr', 'mnopqr', 'lmnopqr', 'lmnopqr', 'nopqr', 'nopqr', 'lmnopqr', 'mnopqr', 'klmnopqrs', 'mnopqr', 'nopqr', 'mnopqr', 'nopqr', 'nopqr', 'lmnopqr', 'nopqr', 'mnopqr', 'nopqr', 'nopqr', 'mnopqr', 'nopqr', 'nopqrs', 'mnopqr', 'nopqr', 'mnopqr', 'lmnopqr', 'lmnopqrs'], 32: ['nopqrstuvwx', 'lmnopqrstuv', 'klmnopqrstu', 'jklmnopqrst', 'hijklmnopqr', 'lmnopqrstuv', 'klmnopqrstu', 'hijklmnopqr', 'nopqrstuvwx', 'lmnopqrstuv', 'klmnopqrstu', 'jklmnopqrst', 'hijklmnopqr', 'lmnopqrstuv', 'klmnopqrstu', 'hijklmnopqr', 'nopqrstuvwx', 'lmnopqrstuv', 'klmnopqrstu', 'jklmnopqrst', 'hijklmnopqr', 'lmnopqrstuv', 'klmnopqrstu', 'hijklmnopqr', 'nopqrstuvwx', 'lmnopqrstuv', 'klmnopqrstu', 'jklmnopqrst', 'hijklmnopqr', 'lmnopqrstuv', 'klmnopqrstu', 'hijklmnopqr'], 33: ['nopqr', 'nopqr', 'mnopqr', 'nopqr', 'lmnopqr', 'mnopqr', 'mnopqrst', 'nopqr', 'mnopqrs', 'mnopqr', 'nopqr', 'nopqr', 'lmnopqrs', 'lmnopqr', 'nopqr', 'lmnopqr', 'nopqr', 'lmnopqr', 'lmnopqr', 'nopqr', 'mnopqr', 'mnopqrs', 'klmnopqr', 'mnopqr', 'nopqr', 'mnopqr', 'lmnopqr', 'mnopqr', 'nopqrst', 'lmnopqr', 'nopqrstu', 'lmnopqr', 'mnopqr'], 34: ['mnopqr', 'lmnopqr', 'mnopqr', 'lmnopqr', 'nopqr', 'lmnopqr', 'lmnopqr', 'lmnopqr', 'nopqr', 'lmnopqr', 'nopqr', 'lmnopqr', 'mnopqrs', 'lmnopqr', 'mnopqr', 'lmnopqr', 'nopqrs', 'lmnopqr', 'nopqr', 'lmnopqr', 'nopqr', 'lmnopqr', 'nopqr', 'lmnopqrs', 'mnopqrs', 'lmnopqrs', 'nopqrs', 'lmnopqr', 'nopqr', 'lmnopqrs', 'nopqr', 'lmnopqr', 'nopqr', 'lmnopqr'], 35: ['lmnopqr', 'mnopqr', 'nopqrs', 'nopqr', 'lmnopqr', 'mnopqr', 'nopqrs', 'lmnopqr', 'mnopqr', 'mnopqr', 'nopqr', 'mnopqr', 'nopqrs', 'nopqrs', 'mnopqr', 'lmnopqr', 'nopqr', 'lmnopqr', 'klmnopqrs', 'klmnopqr', 'nopqr', 'klmnopqr', 'mnopqr', 'nopqrs', 'mnopqr', 'mnopqr', 'lmnopqr', 'nopqr', 'lmnopqr', 'lmnopqrs', 'lmnopqr', 'nopqr', 'lmnopqr', 'nopqr', 'lmnopqr'], 36: ['nopqr', 'lmnopqrstuv', 'klmnopqrstu', 'jklmnopqr', 'nopqr', 'lmnopqrstuv', 'klmnopqrstu', 'jklmnopqr', 'mnopqr', 'lmnopqrstuv', 'klmnopqrstu', 'jklmnopqr', 'nopqr', 'lmnopqrstuv', 'klmnopqrstu', 'jklmnopqr', 'nopqr', 'lmnopqrstuv', 'klmnopqrstu', 'jklmnopqr', 'mnopqr', 'lmnopqrstuv', 'klmnopqrstu', 'jklmnopqr', 'nopqr', 'lmnopqrstuv', 'klmnopqrstu', 'jklmnopqr', 'nopqr', 'lmnopqrstuv', 'klmnopqrstu', 'jklmnopqr', 'nopqr', 'lmnopqrstuv', 'klmnopqrstu', 'jklmnopqr'], 37: ['lmnopqr', 'mnopqr', 'lmnopqrs', 'lmnopqr', 'lmnopqr', 'lmnopqrs', 'mnopqrst', 'lmnopqr', 'lmnopqr', 'mnopqr', 'nopqr', 'nopqrs', 'mnopqr', 'nopqr', 'lmnopqrs', 'nopqr', 'nopqr', 'nopqr', 'mnopqr', 'mnopqr', 'nopqr', 'nopqr', 'mnopqr', 'nopqr', 'lmnopqr', 'klmnopqrs', 'lmnopqr', 'nopqr', 'mnopqr', 'nopqrst', 'mnopqr', 'lmnopqr', 'lmnopqr', 'lmnopqr', 'nopqr', 'nopqr', 'klmnopqr'], 38: ['nopqr', 'lmnopqr', 'nopqr', 'lmnopqr', 'nopqr', 'lmnopqr', 'klmnopqr', 'lmnopqr', 'nopqrs', 'lmnopqr', 'mnopqrs', 'lmnopqr', 'nopqr', 'lmnopqr', 'lmnopqr', 'lmnopqr', 'mnopqr', 'lmnopqr', 'nopqr', 'lmnopqr', 'nopqr', 'lmnopqr', 'mnopqr', 'lmnopqr', 'lmnopqr', 'lmnopqr', 'mnopqrst', 'lmnopqr', 'nopqr', 'lmnopqrst', 'lmnopqr', 'lmnopqr', 'nopqrs', 'lmnopqr', 'nopqr', 'lmnopqr', 'mnopqr', 'lmnopqr'], 39: ['mnopqr', 'nopqr', 'lmnopqr', 'klmnopqr', 'nopqrs', 'nopqr', 'nopqr', 'nopqrs', 'mnopqrs', 'nopqrs', 'klmnopqr', 'mnopqr', 'jklmnopqr', 'nopqr', 'mnopqr', 'klmnopqr', 'mnopqr', 'lmnopqr', 'lmnopqr', 'lmnopqrs', 'klmnopqr', 'nopqr', 'lmnopqr', 'nopqr', 'lmnopqr', 'lmnopqr', 'mnopqrs', 'mnopqrs', 'nopqr', 'mnopqr', 'lmnopqr', 'nopqr', 'mnopqr', 'lmnopqr', 'klmnopqr', 'lmnopqr', 'nopqr', 'mnopqr', 'mnopqr'], 40: ['nopqrstuvwx', 'lmnopqrstuv', 'klmnopqrstu', 'jklmnopqrst', 'hijklmnopqr', 'lmnopqrstuv', 'klmnopqrstu', 'hijklmnopqr', 'nopqrstuvwx', 'lmnopqrstuv', 'klmnopqrstu', 'jklmnopqrst', 'hijklmnopqr', 'lmnopqrstuv', 'klmnopqrstu', 'ghijklmnopqr', 'nopqrstuvwx', 'lmnopqrstuv', 'klmnopqrstu', 'jklmnopqrst', 'hijklmnopqr', 'lmnopqrstuv', 'klmnopqrstu', 'hijklmnopqr', 'mnopqrstuvwx', 'lmnopqrstuv', 'klmnopqrstu', 'jklmnopqrst', 'hijklmnopqr', 'lmnopqrstuv', 'klmnopqrstu', 'hijklmnopqr', 'nopqrstuvwx', 'lmnopqrstuv', 'klmnopqrstu', 'jklmnopqrst', 'hijklmnopqr', 'lmnopqrstuv', 'klmnopqrstu', 'hijklmnopqr'], 41: ['lmnopqr', 'klmnopqr', 'mnopqr', 'nopqr', 'nopqrs', 'mnopqr', 'mnopqrs', 'mnopqrs', 'lmnopqr', 'nopqr', 'lmnopqr', 'nopqr', 'mnopqr', 'lmnopqrst', 'mnopqr', 'nopqrs', 'klmnopqrs', 'lmnopqrs', 'mnopqr', 'nopqrs', 'lmnopqr', 'lmnopqr', 'lmnopqrstu', 'nopqr', 'klmnopqr', 'lmnopqr', 'lmnopqr', 'mnopqr', 'mnopqr', 'lmnopqr', 'nopqrs', 'lmnopqr', 'nopqr', 'lmnopqr', 'nopqr', 'nopqrst', 'nopqr', 'lmnopqr', 'nopqr', 'lmnopqrst', 'lmnopqr'], 42: ['lmnopqr', 'lmnopqr', 'mnopqr', 'lmnopqr', 'lmnopqr', 'lmnopqr', 'nopqr', 'klmnopqrs', 'mnopqrs', 'lmnopqr', 'nopqr', 'lmnopqrs', 'nopqrs', 'lmnopqr', 'mnopqr', 'lmnopqr', 'nopqrs', 'lmnopqr', 'mnopqrs', 'lmnopqr', 'nopqr', 'lmnopqr', 'mnopqr', 'klmnopqrs', 'nopqr', 'lmnopqr', 'klmnopqr', 'lmnopqr', 'klmnopqr', 'lmnopqr', 'nopqrs', 'lmnopqr', 'mnopqr', 'lmnopqrs', 'nopqr', 'lmnopqr', 'mnopqr', 'lmnopqr', 'nopqrs', 'klmnopqr', 'nopqr', 'lmnopqr'], 43: ['lmnopqr', 'lmnopqr', 'mnopqr', 'lmnopqr', 'nopqrs', 'lmnopqrs', 'nopqr', 'lmnopqr', 'lmnopqrs', 'lmnopqr', 'lmnopqrs', 'nopqr', 'nopqr', 'lmnopqr', 'nopqrst', 'lmnopqrs', 'nopqr', 'nopqr', 'lmnopqr', 'lmnopqrs', 'mnopqr', 'mnopqr', 'lmnopqr', 'nopqr', 'klmnopqrs', 'lmnopqr', 'mnopqrs', 'nopqrstu', 'mnopqr', 'mnopqr', 'lmnopqr', 'mnopqrst', 'nopqr', 'nopqrs', 'mnopqr', 'mnopqr', 'nopqr', 'mnopqrs', 'lmnopqr', 'mnopqr', 'nopqr', 'lmnopqr', 'nopqr'], 44: ['nopqr', 'lmnopqrstuv', 'klmnopqrstu', 'jklmnopqr', 'klmnopqr', 'lmnopqrstuv', 'klmnopqrstu', 'jklmnopqr', 'nopqr', 'lmnopqrstuv', 'klmnopqrstu', 'jklmnopqr', 'nopqr', 'lmnopqrstuv', 'klmnopqrstu', 'jklmnopqr', 'nopqr', 'lmnopqrstuv', 'klmnopqrstu', 'jklmnopqr', 'mnopqr', 'lmnopqrstuv', 'klmnopqrstu', 'jklmnopqr', 'nopqr', 'lmnopqrstuv', 'klmnopqrstu', 'jklmnopqr', 'nopqr', 'lmnopqrstuv', 'klmnopqrstu', 'ijklmnopqr', 'nopqr', 'klmnopqrstuv', 'klmnopqrstu', 'jklmnopqr', 'nopqr', 'lmnopqrstuv', 'klmnopqrstu', 'jklmnopqrs', 'nopqrs', 'lmnopqrstuv', 'klmnopqrstu', 'jklmnopqr'], 45: ['nopqr', 'nopqr', 'lmnopqr', 'mnopqr', 'lmnopqr', 'nopqr', 'mnopqrs', 'nopqr', 'mnopqrs', 'mnopqr', 'lmnopqr', 'mnopqr', 'nopqr', 'lmnopqr', 'klmnopqrs', 'lmnopqr', 'nopqr', 'lmnopqr', 'lmnopqrs', 'lmnopqr', 'mnopqr', 'mnopqr', 'nopqr', 'nopqr', 'lmnopqrstu', 'nopqrs', 'klmnopqrs', 'lmnopqr', 'nopqr', 'mnopqr', 'klmnopqr', 'lmnopqr', 'lmnopqrs', 'nopqr', 'lmnopqr', 'mnopqr', 'nopqr', 'lmnopqrs', 'mnopqr', 'lmnopqr', 'klmnopqrs', 'mnopqr', 'nopqr', 'nopqrs', 'mnopqr'], 46: ['nopqr', 'lmnopqrs', 'mnopqr', 'lmnopqr', 'nopqrs', 'lmnopqrs', 'nopqr', 'lmnopqr', 'nopqr', 'klmnopqr', 'nopqrs', 'lmnopqr', 'nopqr', 'lmnopqr', 'mnopqr', 'lmnopqr', 'mnopqrs', 'lmnopqr', 'klmnopqr', 'lmnopqr', 'mnopqr', 'lmnopqr', 'nopqr', 'lmnopqr', 'nopqr', 'klmnopqr', 'klmnopqrs', 'lmnopqr', 'mnopqr', 'lmnopqr', 'mnopqr', 'jklmnopqr', 'mnopqr', 'lmnopqrs', 'nopqr', 'lmnopqr', 'nopqr', 'lmnopqrs', 'nopqr', 'lmnopqr', 'mnopqr', 'lmnopqr', 'mnopqrs', 'lmnopqr', 'nopqr', 'lmnopqr'], 47: ['mnopqrs', 'nopqrs', 'mnopqr', 'lmnopqrs', 'lmnopqr', 'mnopqr', 'klmnopqrst', 'lmnopqr', 'mnopqr', 'lmnopqr', 'nopqrstu', 'nopqr', 'mnopqr', 'nopqrs', 'klmnopqr', 'klmnopqrst', 'mnopqr', 'lmnopqr', 'mnopqr', 'mnopqr', 'nopqr', 'nopqr', 'lmnopqr', 'klmnopqrs', 'nopqr', 'mnopqr', 'nopqrstu', 'klmnopqr', 'lmnopqr', 'mnopqr', 'mnopqrs', 'nopqr', 'lmnopqrs', 'mnopqrst', 'lmnopqr', 'nopqrs', 'lmnopqr', 'mnopqr', 'lmnopqr', 'lmnopqr', 'mnopqr', 'mnopqr', 'lmnopqr', 'mnopqrs', 'nopqr', 'nopqr', 'lmnopqr'], 48: ['nopqrstuvwx', 'lmnopqrstuv', 'klmnopqrstu', 'jklmnopqrst', 'hijklmnopqr', 'lmnopqrstuv', 'klmnopqrstu', 'hijklmnopqr', 'mnopqrstuvwx', 'lmnopqrstuv', 'klmnopqrstu', 'jklmnopqrst', 'hijklmnopqrs', 'lmnopqrstuv', 'klmnopqrstu', 'hijklmnopqr', 'nopqrstuvwx', 'lmnopqrstuv', 'klmnopqrstu', 'jklmnopqrst', 'hijklmnopqr', 'lmnopqrstuv', 'klmnopqrstu', 'hijklmnopqr', 'nopqrstuvwx', 'lmnopqrstuv', 'klmnopqrstu', 'jklmnopqrst', 'hijklmnopqr', 'lmnopqrstuv', 'klmnopqrstu', 'hijklmnopqr', 'nopqrstuvwx', 'lmnopqrstuv', 'klmnopqrstu', 'jklmnopqrst', 'ghijklmnopqr', 'lmnopqrstuv', 'klmnopqrstu', 'hijklmnopqr', 'nopqrstuvwx', 'lmnopqrstuv', 'klmnopqrstu', 'jklmnopqrst', 'hijklmnopqr', 'lmnopqrstuv', 'klmnopqrstu', 'hijklmnopqr'], 49: ['mnopqr', 'lmnopqr', 'lmnopqrs', 'lmnopqr', 'mnopqr', 'lmnopqrs', 'nopqr', 'lmnopqr', 'mnopqrs', 'nopqrs', 'nopqr', 'klmnopqr', 'nopqr', 'nopqr', 'lmnopqr', 'mnopqr', 'lmnopqrs', 'nopqr', 'mnopqrs', 'mnopqr', 'nopqr', 'lmnopqr', 'mnopqrst', 'nopqr', 'mnopqr', 'mnopqrst', 'mnopqrstu', 'lmnopqr', 'lmnopqr', 'mnopqr', 'lmnopqrs', 'mnopqr', 'lmnopqr', 'nopqrs', 'nopqr', 'lmnopqr', 'mnopqr', 'nopqr', 'nopqr', 'lmnopqr', 'nopqr', 'nopqr', 'klmnopqr', 'lmnopqrs', 'lmnopqr', 'nopqrs', 'mnopqr', 'lmnopqr', 'klmnopqrst'], 50: ['mnopqrst', 'lmnopqr', 'nopqr', 'lmnopqrst', 'lmnopqrs', 'lmnopqr', 'nopqr', 'lmnopqr', 'nopqrs', 'lmnopqr', 'nopqr', 'klmnopqrs', 'klmnopqrs', 'lmnopqrs', 'mnopqrs', 'lmnopqrs', 'mnopqr', 'lmnopqrs', 'mnopqr', 'lmnopqr', 'mnopqr', 'lmnopqr', 'klmnopqr', 'lmnopqr', 'klmnopqr', 'lmnopqr', 'mnopqr', 'lmnopqr', 'nopqr', 'lmnopqrs', 'nopqr', 'lmnopqrst', 'nopqr', 'lmnopqr', 'lmnopqr', 'lmnopqr', 'nopqr', 'lmnopqr', 'mnopqrs', 'lmnopqr', 'mnopqrs', 'lmnopqr', 'lmnopqr', 'lmnopqr', 'mnopqr', 'lmnopqr', 'nopqrs', 'lmnopqr', 'mnopqr', 'klmnopqr'], 51: ['lmnopqr', 'mnopqr', 'mnopqr', 'nopqrs', 'nopqr', 'mnopqr', 'lmnopqrs', 'lmnopqrs', 'mnopqr', 'lmnopqrs', 'lmnopqr', 'lmnopqr', 'mnopqrs', 'lmnopqr', 'lmnopqr', 'lmnopqrs', 'lmnopqrs', 'mnopqr', 'nopqr', 'lmnopqr', 'lmnopqr', 'lmnopqr', 'nopqr', 'lmnopqr', 'lmnopqr', 'lmnopqrs', 'nopqr', 'nopqr', 'nopqrs', 'mnopqrs', 'klmnopqr', 'klmnopqr', 'mnopqr', 'nopqr', 'lmnopqr', 'lmnopqr', 'lmnopqr', 'nopqr', 'klmnopqrst', 'jklmnopqrs', 'lmnopqr', 'mnopqr', 'nopqrst', 'nopqrs', 'mnopqr', 'klmnopqr', 'mnopqrs', 'nopqr', 'mnopqr', 'nopqr', 'klmnopqr'], 52: ['nopqr', 'lmnopqrstuv', 'klmnopqrstu', 'jklmnopqr', 'nopqr', 'lmnopqrstuv', 'klmnopqrstu', 'jklmnopqr', 'nopqr', 'lmnopqrstuv', 'klmnopqrstu', 'jklmnopqr', 'mnopqr', 'lmnopqrstuv', 'klmnopqrstu', 'jklmnopqr', 'mnopqr', 'lmnopqrstuv', 'klmnopqrstu', 'jklmnopqr', 'nopqr', 'lmnopqrstuv', 'klmnopqrstu', 'jklmnopqr', 'mnopqr', 'lmnopqrstuv', 'klmnopqrstu', 'hijklmnopqr', 'nopqr', 'lmnopqrstuv', 'klmnopqrstu', 'jklmnopqr', 'nopqrstu', 'lmnopqrstuv', 'klmnopqrstu', 'jklmnopqr', 'nopqr', 'lmnopqrstuv', 'klmnopqrstu', 'ijklmnopqrs', 'nopqrs', 'lmnopqrstuv', 'klmnopqrstu', 'jklmnopqr', 'nopqr', 'lmnopqrstuv', 'klmnopqrstu', 'jklmnopqr', 'nopqr', 'lmnopqrstuv', 'klmnopqrstu', 'jklmnopqr'], 53: ['mnopqr', 'lmnopqr', 'lmnopqr', 'nopqrst', 'lmnopqrst', 'mnopqrs', 'nopqr', 'jklmnopqrs', 'lmnopqrs', 'mnopqr', 'lmnopqrs', 'nopqr', 'lmnopqr', 'lmnopqr', 'lmnopqr', 'nopqr', 'mnopqr', 'mnopqr', 'nopqrs', 'nopqr', 'mnopqr', 'lmnopqr', 'nopqr', 'klmnopqr', 'mnopqr', 'nopqr', 'mnopqr', 'lmnopqrs', 'klmnopqr', 'lmnopqr', 'nopqr', 'klmnopqrs', 'mnopqr', 'nopqrst', 'lmnopqr', 'lmnopqr', 'lmnopqr', 'mnopqr', 'lmnopqr', 'mnopqrs', 'klmnopqr', 'mnopqrst', 'nopqrs', 'lmnopqr', 'nopqr', 'nopqr', 'lmnopqrs', 'klmnopqr', 'lmnopqrst', 'nopqrstu', 'lmnopqr', 'nopqr', 'lmnopqr'], 54: ['mnopqrs', 'lmnopqr', 'klmnopqr', 'lmnopqr', 'lmnopqr', 'lmnopqr', 'lmnopqrs', 'lmnopqr', 'klmnopqr', 'lmnopqrs', 'nopqrs', 'lmnopqr', 'nopqr', 'lmnopqr', 'nopqr', 'lmnopqrs', 'nopqr', 'klmnopqr', 'klmnopqr', 'lmnopqrs', 'mnopqr', 'lmnopqr', 'klmnopqr', 'klmnopqrst', 'nopqr', 'lmnopqr', 'lmnopqr', 'lmnopqr', 'lmnopqr', 'lmnopqr', 'klmnopqr', 'lmnopqr', 'nopqr', 'klmnopqrst', 'nopqr', 'lmnopqr', 'nopqr', 'lmnopqr', 'mnopqrs', 'lmnopqr', 'nopqrstu', 'lmnopqrs', 'nopqrs', 'lmnopqrst', 'mnopqr', 'klmnopqr', 'nopqrst', 'lmnopqr', 'lmnopqrs', 'lmnopqr', 'mnopqr', 'lmnopqr', 'nopqr', 'lmnopqr'], 55: ['nopqr', 'nopqr', 'nopqrs', 'nopqr', 'lmnopqrst', 'lmnopqrst', 'nopqrst', 'lmnopqrstu', 'klmnopqrs', 'lmnopqr', 'mnopqr', 'klmnopqr', 'nopqr', 'nopqr', 'lmnopqr', 'lmnopqr', 'nopqrs', 'lmnopqrs', 'mnopqr', 'lmnopqr', 'klmnopqr', 'mnopqr', 'klmnopqr', 'mnopqr', 'lmnopqr', 'mnopqr', 'lmnopqr', 'lmnopqr', 'lmnopqrs', 'lmnopqrs', 'nopqrstu', 'mnopqr', 'lmnopqr', 'nopqrs', 'lmnopqr', 'mnopqr', 'mnopqr', 'lmnopqr', 'mnopqrst', 'mnopqrst', 'nopqr', 'nopqr', 'klmnopqr', 'nopqrs', 'klmnopqr', 'lmnopqr', 'lmnopqrs', 'nopqr', 'lmnopqrs', 'mnopqr', 'klmnopqr', 'lmnopqr', 'nopqr', 'mnopqr', 'mnopqr'], 56: ['mnopqrstuvwx', 'lmnopqrstuv', 'klmnopqrstu', 'jklmnopqrst', 'hijklmnopqr', 'lmnopqrstuv', 'klmnopqrstu', 'hijklmnopqr', 'mnopqrstuvwx', 'lmnopqrstuv', 'klmnopqrstu', 'jklmnopqrst', 'hijklmnopqr', 'lmnopqrstuv', 'klmnopqrstu', 'hijklmnopqr', 'nopqrstuvwx', 'lmnopqrstuv', 'klmnopqrstu', 'jklmnopqrst', 'hijklmnopqr', 'lmnopqrstuv', 'klmnopqrstu', 'hijklmnopqr', 'nopqrstuvwx', 'lmnopqrstuv', 'klmnopqrstu', 'jklmnopqrst', 'hijklmnopqr', 'lmnopqrstuv', 'klmnopqrstu', 'hijklmnopqr', 'mnopqrstuvwx', 'lmnopqrstuv', 'klmnopqrstu', 'jklmnopqrst', 'hijklmnopqr', 'lmnopqrstuv', 'klmnopqrstu', 'hijklmnopqr', 'nopqrstuvwx', 'lmnopqrstuv', 'klmnopqrstu', 'jklmnopqrst', 'hijklmnopqr', 'lmnopqrstuv', 'klmnopqrstu', 'hijklmnopqr', 'nopqrstuvwx', 'lmnopqrstuv', 'klmnopqrstu', 'jklmnopqrst', 'ghijklmnopqr', 'lmnopqrstuv', 'klmnopqrstu', 'hijklmnopqr'], 57: ['nopqrs', 'nopqrs', 'klmnopqr', 'klmnopqr', 'mnopqr', 'klmnopqr', 'lmnopqrs', 'mnopqrst', 'mnopqr', 'mnopqr', 'lmnopqrst', 'klmnopqr', 'nopqr', 'nopqr', 'lmnopqrs', 'nopqr', 'lmnopqr', 'mnopqrs', 'nopqr', 'klmnopqrs', 'mnopqr', 'lmnopqr', 'lmnopqr', 'mnopqr', 'lmnopqrs', 'lmnopqr', 'lmnopqrst', 'mnopqrs', 'nopqrs', 'mnopqrst', 'lmnopqr', 'lmnopqr', 'lmnopqrs', 'klmnopqrs', 'nopqr', 'mnopqrs', 'klmnopqr', 'nopqr', 'nopqr', 'nopqr', 'nopqr', 'mnopqr', 'nopqrs', 'lmnopqr', 'klmnopqr', 'mnopqr', 'nopqrs', 'klmnopqr', 'klmnopqrs', 'lmnopqrst', 'nopqr', 'klmnopqr', 'lmnopqr', 'lmnopqr', 'lmnopqrstu', 'lmnopqr', 'mnopqrs'], 58: ['mnopqrs', 'lmnopqr', 'nopqr', 'lmnopqrs', 'klmnopqrs', 'lmnopqr', 'nopqrs', 'lmnopqr', 'klmnopqr', 'lmnopqr', 'nopqr', 'lmnopqrs', 'nopqrs', 'lmnopqrs', 'mnopqr', 'lmnopqrs', 'lmnopqr', 'lmnopqrst', 'mnopqrs', 'lmnopqr', 'nopqr', 'lmnopqrs', 'klmnopqrs', 'lmnopqrs', 'mnopqrs', 'klmnopqr', 'mnopqr', 'lmnopqr', 'nopqr', 'lmnopqr', 'nopqr', 'lmnopqr', 'nopqr', 'lmnopqr', 'nopqr', 'lmnopqr', 'mnopqr', 'lmnopqr', 'lmnopqrs', 'lmnopqrs', 'lmnopqr', 'lmnopqrs', 'nopqrst', 'klmnopqr', 'nopqr', 'lmnopqrs', 'nopqr', 'klmnopqrs', 'mnopqr', 'lmnopqr', 'mnopqr', 'lmnopqrs', 'mnopqr', 'lmnopqr', 'klmnopqr', 'lmnopqr', 'mnopqrs', 'lmnopqrs'], 59: ['mnopqrst', 'nopqrs', 'lmnopqr', 'mnopqr', 'klmnopqr', 'mnopqr', 'nopqr', 'klmnopqrs', 'klmnopqr', 'klmnopqr', 'lmnopqrs', 'lmnopqr', 'klmnopqr', 'lmnopqr', 'lmnopqr', 'nopqrstu', 'lmnopqr', 'lmnopqr', 'nopqr', 'lmnopqr', 'mnopqr', 'nopqr', 'nopqrs', 'mnopqrs', 'nopqrstu', 'nopqrs', 'nopqr', 'lmnopqrs', 'klmnopqrs', 'klmnopqr', 'mnopqr', 'nopqrs', 'klmnopqrs', 'lmnopqr', 'klmnopqr', 'lmnopqr', 'mnopqr', 'lmnopqrs', 'mnopqr', 'lmnopqr', 'lmnopqr', 'nopqr', 'mnopqr', 'mnopqrs', 'klmnopqr', 'klmnopqrs', 'lmnopqrs', 'lmnopqr', 'lmnopqrst', 'nopqrs', 'mnopqr', 'mnopqr', 'lmnopqr', 'nopqr', 'lmnopqrst', 'mnopqr', 'nopqrs', 'lmnopqr', 'nopqr'], 60: ['nopqrs', 'lmnopqrstuv', 'klmnopqrstu', 'jklmnopqrs', 'lmnopqr', 'lmnopqrstuv', 'klmnopqrstu', 'ijklmnopqrs', 'nopqr', 'lmnopqrstuv', 'klmnopqrstu', 'jklmnopqr', 'nopqr', 'lmnopqrstuv', 'klmnopqrstu', 'jklmnopqr', 'nopqr', 'lmnopqrstuv', 'klmnopqrstu', 'jklmnopqr', 'nopqr', 'lmnopqrstuv', 'klmnopqrstu', 'jklmnopqr', 'mnopqrs', 'lmnopqrstuv', 'klmnopqrstu', 'jklmnopqr', 'nopqrs', 'lmnopqrstuv', 'klmnopqrstuv', 'jklmnopqr', 'klmnopqr', 'lmnopqrstuv', 'klmnopqrstu', 'jklmnopqr', 'nopqr', 'lmnopqrstuv', 'klmnopqrstu', 'jklmnopqr', 'nopqr', 'lmnopqrstuv', 'klmnopqrstu', 'jklmnopqr', 'mnopqr', 'lmnopqrstuv', 'klmnopqrstu', 'hijklmnopqr', 'nopqr', 'lmnopqrstuvw', 'klmnopqrstu', 'ijklmnopqr', 'nopqr', 'lmnopqrstuv', 'klmnopqrstu', 'jklmnopqr', 'mnopqr', 'lmnopqrstuv', 'klmnopqrstu', 'ijklmnopqrs'], 61: ['klmnopqr', 'lmnopqrst', 'klmnopqr', 'nopqrst', 'lmnopqr', 'lmnopqr', 'lmnopqr', 'lmnopqr', 'nopqr', 'mnopqrst', 'mnopqr', 'jklmnopqr', 'lmnopqr', 'lmnopqr', 'lmnopqr', 'lmnopqrs', 'klmnopqr', 'mnopqr', 'lmnopqr', 'nopqrs', 'lmnopqr', 'lmnopqrs', 'nopqrs', 'lmnopqrst', 'lmnopqr', 'nopqr', 'lmnopqr', 'nopqr', 'klmnopqrs', 'mnopqr', 'lmnopqr', 'lmnopqrs', 'klmnopqr', 'nopqr', 'klmnopqr', 'nopqr', 'mnopqr', 'mnopqr', 'klmnopqr', 'lmnopqr', 'nopqrs', 'mnopqr', 'lmnopqr', 'lmnopqr', 'nopqr', 'lmnopqrst', 'klmnopqr', 'klmnopqr', 'mnopqrs', 'mnopqrst', 'mnopqrs', 'mnopqrst', 'nopqr', 'jklmnopqr', 'lmnopqrstu', 'nopqr', 'mnopqrstu', 'nopqr', 'mnopqr', 'nopqrstu', 'mnopqr'], 62: ['nopqr', 'lmnopqr', 'nopqr', 'lmnopqr', 'lmnopqr', 'lmnopqr', 'klmnopqr', 'lmnopqr', 'nopqr', 'lmnopqrs', 'lmnopqrs', 'lmnopqr', 'klmnopqrs', 'lmnopqr', 'nopqrs', 'lmnopqr', 'nopqrstu', 'lmnopqr', 'lmnopqr', 'klmnopqrst', 'mnopqr', 'lmnopqrs', 'nopqr', 'klmnopqrstuv', 'nopqrs', 'lmnopqrst', 'mnopqr', 'lmnopqr', 'mnopqr', 'lmnopqr', 'lmnopqrst', 'lmnopqrs', 'nopqr', 'lmnopqrstu', 'lmnopqrs', 'lmnopqr', 'mnopqr', 'lmnopqrs', 'klmnopqr', 'lmnopqr', 'nopqr', 'lmnopqr', 'mnopqr', 'klmnopqrst', 'mnopqr', 'lmnopqr', 'mnopqrs', 'lmnopqr', 'nopqrst', 'lmnopqr', 'nopqr', 'lmnopqrstu', 'nopqr', 'lmnopqrs', 'mnopqr', 'lmnopqr', 'nopqrs', 'lmnopqrs', 'nopqr', 'lmnopqrs', 'klmnopqr', 'klmnopqrs'], 63: ['lmnopqr', 'mnopqr', 'mnopqr', 'lmnopqr', 'lmnopqr', 'klmnopqr', 'lmnopqr', 'klmnopqr', 'mnopqr', 'lmnopqr', 'nopqrst', 'mnopqr', 'mnopqrs', 'lmnopqr', 'lmnopqrst', 'mnopqrs', 'nopqr', 'klmnopqr', 'klmnopqr', 'nopqr', 'lmnopqr', 'lmnopqr', 'lmnopqr', 'klmnopqr', 'nopqr', 'lmnopqrst', 'lmnopqrs', 'nopqr', 'klmnopqrstu', 'mnopqr', 'klmnopqrs', 'lmnopqr', 'mnopqrs', 'nopqrst', 'nopqr', 'mnopqr', 'lmnopqr', 'lmnopqrs', 'mnopqr', 'mnopqrs', 'nopqrs', 'nopqr', 'lmnopqr', 'mnopqrs', 'klmnopqr', 'nopqrs', 'klmnopqr', 'klmnopqr', 'nopqrs', 'klmnopqrs', 'mnopqrs', 'nopqrs', 'klmnopqr', 'mnopqr', 'mnopqrs', 'nopqr', 'lmnopqr', 'lmnopqr', 'klmnopqrs', 'nopqrs', 'klmnopqrs', 'mnopqr', 'klmnopqrs'], 64: ['mnopqrstuvwx', 'klmnopqrstuv', 'klmnopqrstu', 'jklmnopqrst', 'hijklmnopqr', 'lmnopqrstuv', 'klmnopqrstu', 'hijklmnopqr', 'nopqrstuvwx', 'lmnopqrstuv', 'klmnopqrstu', 'jklmnopqrst', 'hijklmnopqr', 'lmnopqrstuv', 'klmnopqrstu', 'hijklmnopqr', 'nopqrstuvwx', 'lmnopqrstuv', 'klmnopqrstu', 'jklmnopqrst', 'hijklmnopqr', 'lmnopqrstuv', 'klmnopqrstu', 'hijklmnopqr', 'nopqrstuvwx', 'lmnopqrstuv', 'jklmnopqrstu', 'jklmnopqrst', 'hijklmnopqr', 'lmnopqrstuv', 'klmnopqrstu', 'hijklmnopqr', 'nopqrstuvwx', 'lmnopqrstuv', 'klmnopqrstu', 'jklmnopqrst', 'hijklmnopqr', 'lmnopqrstuv', 'klmnopqrstu', 'hijklmnopqr', 'nopqrstuvwx', 'lmnopqrstuv', 'klmnopqrstu', 'jklmnopqrst', 'hijklmnopqr', 'lmnopqrstuv', 'klmnopqrstu', 'hijklmnopqr', 'nopqrstuvwx', 'lmnopqrstuv', 'klmnopqrstu', 'jklmnopqrst', 'hijklmnopqr', 'lmnopqrstuv', 'klmnopqrstu', 'hijklmnopqr', 'nopqrstuvwx', 'lmnopqrstuv', 'klmnopqrstu', 'jklmnopqrst', 'hijklmnopqr', 'lmnopqrstuv', 'klmnopqrstu', 'hijklmnopqr']}



```python
from itertools import product
with open('eae.txt', 'w') as f:
    for klen, kopts in kd.items():
        break # cancel this
        print(klen)
        for karr in product(*kopts):
            f.write(devig(ct, ''.join(karr)) + '\n\n')
```


```python
for k, v in kd.items():
    print(k, end=' ')
    for ind in range(16):
        i = v[ind % len(v)]
        x = ''
        for j in range(len(i)):
            x += cshift(ct[ind], i[j], rev=True)
        print(x, end=' ')
    print()
```

    1 srqpo rqpon mlkji gfedc ihgfe wvuts lkjih lkjih kjihg vutsr hgfed qponm fedcb srqpo hgfed onmlk 
    2 srqpo tsrqpon mlkji ihgfedc ihgfe yxwvuts lkjih nmlkjih kjihg xwvutsr hgfed srqponm fedcb utsrqpo hgfed qponmlk 
    3 srqpo rqpon mlkji gfedc ihgfe wvuts lkjih lkjih kjihg vutsr hgfed qponm fedcb srqpo hgfed onmlk 
    4 srqpo tsrqponmlkj ponmlkjihgf kjihgfedc ihgfe yxwvutsrqpo onmlkjihgfe ponmlkjih kjihg xwvutsrqpon kjihgfedcba utsrqponm fedcb utsrqponmlk kjihgfedcba srqponmlk 
    5 srqpo rqpon mlkji gfedc jihgfe wvuts lkjih lkjih kjihg wvutsr hgfed qponm fedcb srqpo ihgfed onmlk 
    6 srqpo tsrqpon mlkji ihgfedc ihgfe yxwvuts lkjih nmlkjih kjihg xwvutsr hgfed srqponm fedcb utsrqpo hgfed qponmlk 
    7 tsrqpo srqpon mlkji gfedc jihgfe wvuts lkjih mlkjih lkjihg vutsr hgfed rqponm fedcb srqpo ihgfed ponmlk 
    8 srqponmlkji tsrqponmlkj ponmlkjihgf kjihgfedcba onmlkjihgfe yxwvutsrqpo onmlkjihgfe rqponmlkjih kjihgfedcba xwvutsrqpon kjihgfedcba utsrqponmlk lkjihgfedcb utsrqponmlk kjihgfedcba utsrqponmlk 
    9 srqpo rqpon nmlkji gfedc ihgfe wvuts lkjih lkjih lkjihg vutsr hgfed rqponm fedcb srqpo hgfed onmlk 
    10 srqpo tsrqpon mlkji ihgfedc jihgfe yxwvuts lkjih nmlkjih kjihg xwvutsr hgfed srqponm fedcb utsrqpo ihgfed qponmlk 
    11 srqpo rqpon mlkji gfedc kjihgfe wvuts lkjih lkjih kjihg wvutsr hgfed qponm fedcb srqpo hgfed qponmlk 
    12 srqpo tsrqponmlkj ponmlkjihgf kjihgfedc ihgfe yxwvutsrqpo onmlkjihgfe ponmlkjih kjihg xwvutsrqpon kjihgfedcba utsrqponm fedcb utsrqponmlk kjihgfedcba srqponmlk 
    13 srqpo rqpon mlkji hgfedc ihgfe wvuts lkjih lkjih kjihg vutsr hgfed rqponm gfedcb srqpo hgfed onmlk 
    14 tsrqpo tsrqpon mlkji ihgfedc jihgfe yxwvuts lkjih nmlkjih lkjihg xwvutsr hgfed srqponm fedcb utsrqpo ihgfed qponmlk 
    15 srqpo rqpon onmlkji gfedc kjihgfe wvuts lkjih lkjih kjihg wvutsr hgfed rqponm fedcb srqpo ihgfed onmlk 
    16 srqponmlkji tsrqponmlkj ponmlkjihgf kjihgfedcba onmlkjihgfe yxwvutsrqpo onmlkjihgfe rqponmlkjih kjihgfedcba xwvutsrqpon kjihgfedcba utsrqponmlk lkjihgfedcb utsrqponmlk kjihgfedcba utsrqponmlk 
    17 tsrqpo rqpon nmlkji gfedc ihgfe wvuts nmlkjih mlkjih kjihg vutsr hgfed qponm gfedcba srqpo ihgfed onmlk 
    18 srqpo tsrqpon nmlkji ihgfedc ihgfe yxwvuts lkjih nmlkjih lkjihg xwvutsr hgfed srqponm fedcb utsrqpo hgfed qponmlk 
    19 srqpo rqpon mlkji hgfedc ihgfe yxwvuts nmlkjih mlkjih kjihg vutsr ihgfedc srqponm fedcb srqpo jihgfed onmlk 
    20 srqpo tsrqponmlkj ponmlkjihgf kjihgfedc jihgfe yxwvutsrqpo onmlkjihgfe ponmlkjih kjihg xwvutsrqpon kjihgfedcba utsrqponm fedcb utsrqponmlk kjihgfedcba srqponmlk 
    21 utsrqpo srqpon nmlkji gfedc kjihgfe yxwvuts lkjih onmlkjih lkjihg vutsr hgfed rqponm fedcba srqpo ihgfed ponmlk 
    22 srqpo tsrqpon mlkji ihgfedc lkjihgfe yxwvuts lkjih nmlkjih kjihg xwvutsr hgfed tsrqponm fedcb utsrqpo hgfed qponmlk 
    23 srqpo rqpon nmlkji ihgfedc ihgfe xwvuts lkjih mlkjih kjihg wvutsr hgfedc qponm fedcb srqpo ihgfed onmlk 
    24 srqponmlkji tsrqponmlkj ponmlkjihgf kjihgfedcba onmlkjihgfe yxwvutsrqpo onmlkjihgfe rqponmlkjih kjihgfedcba xwvutsrqpon kjihgfedcba utsrqponmlk lkjihgfedcb utsrqponmlk kjihgfedcba utsrqponmlk 
    25 tsrqpo srqpon mlkji gfedc kjihgfed wvuts lkjih lkjih kjihg xwvutsr hgfed qponm hgfedcb tsrqpon ihgfed ponmlkj 
    26 srqpo tsrqpon mlkji ihgfedc ihgfe yxwvuts lkjihgfe nmlkjih kjihg xwvutsr hgfed srqponm gfedcb utsrqpon hgfedc qponmlk 
    27 tsrqpo tsrqpon onmlkji ihgfedc kjihgfe wvuts nmlkjihg lkjih mlkjihg vutsr hgfed rqponm fedcb srqpo hgfed onmlkj 
    28 tsrqpo tsrqponmlkj ponmlkjihgf kjihgfedc jihgfe yxwvutsrqpo onmlkjihgfe ponmlkjih lkjihg xwvutsrqpon kjihgfedcba utsrqponm fedcb utsrqponmlk kjihgfedcba srqponmlk 
    29 tsrqpo rqpon mlkji gfedc kjihgfe wvuts lkjih mlkjih mlkjihg xwvutsr hgfed srqponm fedcba srqpon ihgfed onmlk 
    30 srqpon tsrqpon ponmlkji ihgfedcb kjihgfe yxwvuts lkjih nmlkjihg kjihg xwvutsr hgfed srqponm fedcb utsrqpo ihgfed qponmlk 
    31 srqpo rqpon mlkji ihgfedc kjihgfe xwvuts nmlkjih nmlkjih kjihg vutsr jihgfed rqponm ihgfedcba tsrqpo hgfed ponmlk 
    32 srqponmlkji tsrqponmlkj ponmlkjihgf kjihgfedcba onmlkjihgfe yxwvutsrqpo onmlkjihgfe rqponmlkjih kjihgfedcba xwvutsrqpon kjihgfedcba utsrqponmlk lkjihgfedcb utsrqponmlk kjihgfedcba utsrqponmlk 
    33 srqpo rqpon nmlkji gfedc kjihgfe xwvuts mlkjihgf lkjih lkjihgf wvutsr hgfed qponm hgfedcba utsrqpo hgfed qponmlk 
    34 tsrqpo tsrqpon nmlkji ihgfedc ihgfe yxwvuts nmlkjih nmlkjih kjihg xwvutsr hgfed srqponm gfedcba utsrqpo ihgfed qponmlk 
    35 utsrqpo srqpon mlkjih gfedc kjihgfe xwvuts lkjihg nmlkjih lkjihg wvutsr hgfed rqponm fedcba srqpon ihgfed qponmlk 
    36 srqpo tsrqponmlkj ponmlkjihgf kjihgfedc ihgfe yxwvutsrqpo onmlkjihgfe ponmlkjih lkjihg xwvutsrqpon kjihgfedcba utsrqponm fedcb utsrqponmlk kjihgfedcba srqponmlk 
    37 utsrqpo srqpon onmlkjih ihgfedc kjihgfe yxwvutsr mlkjihgf nmlkjih mlkjihg wvutsr hgfed qponml gfedcb srqpo jihgfedc onmlk 
    38 srqpo tsrqpon mlkji ihgfedc ihgfe yxwvuts onmlkjih nmlkjih kjihgf xwvutsr ihgfedc srqponm fedcb utsrqpo jihgfed qponmlk 
    39 tsrqpo rqpon onmlkji jihgfedc ihgfed wvuts lkjih lkjihg lkjihgf vutsrq kjihgfed rqponm jihgfedcb srqpo ihgfed rqponmlk 
    40 srqponmlkji tsrqponmlkj ponmlkjihgf kjihgfedcba onmlkjihgfe yxwvutsrqpo onmlkjihgfe rqponmlkjih kjihgfedcba xwvutsrqpon kjihgfedcba utsrqponmlk lkjihgfedcb utsrqponmlk kjihgfedcba vutsrqponmlk 
    41 utsrqpo utsrqpon nmlkji gfedc ihgfed xwvuts mlkjihg mlkjihg mlkjihg vutsr jihgfed qponm gfedcb utsrqponm ihgfed onmlkj 
    42 utsrqpo tsrqpon nmlkji ihgfedc kjihgfe yxwvuts lkjih onmlkjihg lkjihgf xwvutsr hgfed srqponml fedcba utsrqpo ihgfed qponmlk 
    43 utsrqpo tsrqpon nmlkji ihgfedc ihgfed yxwvutsr lkjih nmlkjih mlkjihgf xwvutsr jihgfedc qponm fedcb utsrqpo hgfedcb qponmlkj 
    44 srqpo tsrqponmlkj ponmlkjihgf kjihgfedc lkjihgfe yxwvutsrqpo onmlkjihgfe ponmlkjih kjihg xwvutsrqpon kjihgfedcba utsrqponm fedcb utsrqponmlk kjihgfedcba srqponmlk 
    45 srqpo rqpon onmlkji hgfedc kjihgfe wvuts mlkjihg lkjih lkjihgf wvutsr jihgfed rqponm fedcb utsrqpo kjihgfedc qponmlk 
    46 srqpo tsrqponm nmlkji ihgfedc ihgfed yxwvutsr lkjih nmlkjih kjihg yxwvutsr hgfedc srqponm fedcb utsrqpo ihgfed qponmlk 
    47 tsrqpon rqponm nmlkji ihgfedcb kjihgfe xwvuts onmlkjihgf nmlkjih lkjihg xwvutsr hgfedcba qponm gfedcb srqpon kjihgfed rqponmlkji 
    48 srqponmlkji tsrqponmlkj ponmlkjihgf kjihgfedcba onmlkjihgfe yxwvutsrqpo onmlkjihgfe rqponmlkjih lkjihgfedcba xwvutsrqpon kjihgfedcba utsrqponmlk lkjihgfedcba utsrqponmlk kjihgfedcba utsrqponmlk 
    49 tsrqpo tsrqpon onmlkjih ihgfedc jihgfe yxwvutsr lkjih nmlkjih lkjihgf vutsrq hgfed tsrqponm fedcb srqpo jihgfed ponmlk 
    50 tsrqponm tsrqpon mlkji ihgfedcba kjihgfed yxwvuts lkjih nmlkjih kjihgf xwvutsr hgfed tsrqponml ihgfedcba utsrqpon ihgfedc qponmlkj 
    51 utsrqpo srqpon nmlkji gfedcb ihgfe xwvuts nmlkjihg nmlkjihg lkjihg xwvutsrq jihgfed srqponm gfedcba utsrqpo jihgfed qponmlkj 
    52 srqpo tsrqponmlkj ponmlkjihgf kjihgfedc ihgfe yxwvutsrqpo onmlkjihgfe ponmlkjih kjihg xwvutsrqpon kjihgfedcba utsrqponm gfedcb utsrqponmlk kjihgfedcba srqponmlk 
    53 tsrqpo tsrqpon onmlkji gfedcba kjihgfedc xwvutsr lkjih ponmlkjihg mlkjihgf wvutsr jihgfedc qponm hgfedcb utsrqpo jihgfed onmlk 
    54 tsrqpon tsrqpon ponmlkji ihgfedc kjihgfe yxwvuts nmlkjihg nmlkjih nmlkjihg xwvutsrq hgfedc srqponm fedcb utsrqpo hgfed qponmlkj 
    55 srqpo rqpon mlkjih gfedc kjihgfedc yxwvutsrq lkjihgf nmlkjihgfe nmlkjihgf xwvutsr ihgfed tsrqponm fedcb srqpo jihgfed qponmlk 
    56 tsrqponmlkji tsrqponmlkj ponmlkjihgf kjihgfedcba onmlkjihgfe yxwvutsrqpo onmlkjihgfe rqponmlkjih lkjihgfedcba xwvutsrqpon kjihgfedcba utsrqponmlk lkjihgfedcb utsrqponmlk kjihgfedcba utsrqponmlk 
    57 srqpon rqponm ponmlkji jihgfedc jihgfe zyxwvuts nmlkjihg mlkjihgf lkjihg wvutsr jihgfedcb tsrqponm fedcb srqpo jihgfedc onmlk 
    58 tsrqpon tsrqpon mlkji ihgfedcb lkjihgfed yxwvuts lkjihg nmlkjih nmlkjihg xwvutsr hgfed srqponml fedcba utsrqpon ihgfed qponmlkj 
    59 tsrqponm rqponm onmlkji hgfedc lkjihgfe xwvuts lkjih onmlkjihg nmlkjihg yxwvutsr jihgfedc srqponm ihgfedcb utsrqpo jihgfed onmlkjih 
    60 srqpon tsrqponmlkj ponmlkjihgf kjihgfedcb kjihgfe yxwvutsrqpo onmlkjihgfe qponmlkjihg kjihg xwvutsrqpon kjihgfedcba utsrqponm fedcb utsrqponmlk kjihgfedcba srqponmlk 
    61 vutsrqpo tsrqponml ponmlkji gfedcba kjihgfe yxwvuts nmlkjih nmlkjih kjihg wvutsrqp ihgfed utsrqponm hgfedcb utsrqpo jihgfed qponmlkj 
    62 srqpo tsrqpon mlkji ihgfedc kjihgfe yxwvuts onmlkjih nmlkjih kjihg xwvutsrq jihgfedc srqponm ihgfedcba utsrqpo hgfedc qponmlk 
    63 utsrqpo srqpon nmlkji ihgfedc kjihgfe zyxwvuts nmlkjih onmlkjih lkjihg xwvutsr hgfedcb rqponm gfedcba utsrqpo jihgfedcb ponmlkj 
    64 tsrqponmlkji utsrqponmlkj ponmlkjihgf kjihgfedcba onmlkjihgfe yxwvutsrqpo onmlkjihgfe rqponmlkjih kjihgfedcba xwvutsrqpon kjihgfedcba utsrqponmlk lkjihgfedcb utsrqponmlk kjihgfedcba utsrqponmlk 



```python
k, v = 8, kd[8]
for ind in range(32):
    i = v[ind % len(v)]
    x = ''
    for j in range(len(i)):
        x += cshift(ct[ind], i[j], rev=True)
    print(x, end=' ')
    print()
```

    srqponmlkji 
    tsrqponmlkj 
    ponmlkjihgf 
    kjihgfedcba 
    onmlkjihgfe 
    yxwvutsrqpo 
    onmlkjihgfe 
    rqponmlkjih 
    kjihgfedcba 
    xwvutsrqpon 
    kjihgfedcba 
    utsrqponmlk 
    lkjihgfedcb 
    utsrqponmlk 
    kjihgfedcba 
    utsrqponmlk 
    kjihgfedcba 
    kjihgfedcba 
    kjihgfedcba 
    kjihgfedcba 
    kjihgfedcba 
    kjihgfedcba 
    kjihgfedcba 
    xwvutsrqpon 
    onmlkjihgfe 
    tsrqponmlkj 
    onmlkjihgfe 
    srqponmlkji 
    onmlkjihgfe 
    onmlkjihgfe 
    ponmlkjihgf 
    mlkjihgfedc 



```python
envig(''.join(alpha), 'zmxhz2rledy0', alphabet=alpha)
```




    'znzk37xsmm8bbzbwfj94yyknnbn8rvlgaawz'




```python
devig(''.join(alpha), 'ehzpzxj1bmrzzwnoemln')
```




    '64nyps7qh73wx1bbmfhgqo7i9cra1rnghlvv'




```python
devig(envig(ct1, ct2), 'dex64')
```




    'we7q1kjymj9k8tqfeqg8f9pjwc8om1rl7hidt3omong64oitqvpf0nori3rqtrxp3adtmooydrloo0r00yh34jvz29wkas3lr4wr6fg8hvsca7xmm2qn5a0n2p6w9nes17mb5w4v2e11zmyjfywcz0dgf05y4frvnn9tcpq65ujsexxnsdks8l1scvq5z0bkc12rlasywnctdot73zpbeqqv19uunp6s5iay7nedbvsox8uvxv4wspi494oqe02lvhv5ss4yicvq0vbs73yn16vxuu8y7tjp7vxlew3rt56xjmtuirn595mkkw2r31y4qkcjvse3z1gsgwqjp9wl2juj3hq8x1mlb0qne0uyqkpnvtc4q5sna2xhxxtmpj5z7envvcgt5s5ll703ijusvnq6o2ubdt7cngr2lldsgjo5o3kmcu3ls5v4uoc0zun0t0dhjtxkhbw1nogo0moxb3x96iknt2v2nr5i8rd2y5ogyrsfu4xwlr4nxmhaoquo4s4p12tlmx9sweix5sjxgqlbn4hw6z42xcnx18ko14tds3lmooaq9seb32ac8t40wbuvmp6u3emu4ueo7zvfu6owsz4n5on911jgxvtlp9t0setkwova0mjsfpuwq7mutx5y6vov51sk9q5ns8xuwh4s8lkw20qoa4rmwcuwhg5p1unb3qmkfy3f39zouu8o1rp51zhj1sxlq3sz0l2zrroz2vjt3l3lx1t7pvvsxni09qstkx1uy5rwwrwq6yraruvj1uwftzjz3q221pna3orkdjqno2prlu2khsb37rgt3vqwqwv3jvf6csrt9wuf8m5qy40wro7u8jrwo0go8t0zxytqrn5nvyj31tyf8n4kv4ioyp4rarl112rd6rw9x339uwfs5ptv1zwx644qnbvugp5lygo37bqx9wsnzyzszs2ygiv04rwdfuyxkto2qes10zp36ssl3m6dn8xx3e3u1qo0x5sd92yimd6o2r155qex5wqv2mxz75q4rz1tz0n0bslwa7zrnd7pvp6wbqoeyywonxkisz9luv4u3jg49wh8k3sf004yxz7yvp0s3rvadowfk5msyh1vfrn60ydm5nxtzdl4v00u4ji4p1sqeuxpsewy4vzvsoixsmoma4ykjcobsozyvjaxz7icaq3tz4w5z04r8uo35ysh9yxgs5yw2p33a1fctpkeau4blh65tiwv9zaubxkkk12hnvzx1xyyzju5asmsgu3svurvzd1t90n98zexbwylw1prkctnw2kz44ilc1yrrvapfk51twvcv3tnbzolrd3nvw846xj043mr5twbth0l2m9t43lbtuec6znnx1qu2n60sed5a2ovkzxzgh4ssygz3a8omwip35oeo'




```python
import base64
def b64en(s):
    return base64.b64encode(bytes(s, 'utf-8')).decode('utf-8')
def b64enmod(s):
    ret = b64en(s).lower()
    if '=' in ret:
        ret = ret[:ret.index('=')]
    return ret
def b64de(s):
    return base64.b64decode(bytes(s, 'utf-8')).decode('utf-8')
```


```python
b64en('de'*64)
```




    'ZGVkZWRlZGVkZWRlZGVkZWRlZGVkZWRlZGVkZWRlZGVkZWRlZGVkZWRlZGVkZWRlZGVkZWRlZGVkZWRlZGVkZWRlZGVkZWRlZGVkZWRlZGVkZWRlZGVkZWRlZGVkZWRlZGVkZWRlZGVkZWRlZGVkZWRlZGVkZWRlZGVkZWRlZGU='




```python
import requests
def bitly(url):
    return requests.get(f"http://bit.ly/{url}")
```


```python
url = b64en('dex64')
bitly(url)
```




    <Response [404]>




```python
from collections import Counter
import matplotlib.pyplot as plt
```


```python
def friedman(t, alphabet=alpha):
    d = dict(Counter(t))
    lt = len(t)
    res = 0
    for k, v in d.items():
        res += v*(v-1)
    res /= lt*(lt-1)
    elen = 0.0265*lt / ((lt-1)*res + 0.065 - 0.038*lt)
    return res, elen

# rules: {coset: [(source, dest)]}
def cosplit(t, n, l=32, rules={}):
    d = {}
    for i in range(n, len(t), n):
        j = (i // n - 1) // l
        if j not in d:
            d[j] = []
        txt = t[i-n:i]
        tlist = list(txt)
        for k, v in rules.items():
            for src, dst in v:
                if tlist[k] == src:
                    tlist[k] = dst
        d[j].append(''.join(tlist))
    for i in range(l - len(d[j])):
        d[j].append('')
    print(pd.DataFrame(d))
    
def coset(t, n):
    lt = len(t)
    for i in range(n):
        cst = t[i::n]
        ctr = dict(Counter(cst))
        print(f"Coset {i}: {''.join(sorted(set(ctr)))}")
        for k, v in sorted(ctr.items(), key=lambda x: x[1], reverse=True):
            print(k, v / lt)
```


```python
cosplit(ct, 16)
```

                       0                 1                 2                 3                 4                 5
    0   54ztv9yyx8u3s5u1  9077y363y79xz26y  102w173z96u5u5yr  1w2w446r1x5vv5yu  4z58v63u89yyx146  2vxtuwwxx396y0yy
    1   xvutrvu414y1vzzt  cavuzavsbv5usw06  1y47330y4wvw1vwy  cvxzuv03978ws79z  ax6703046v2858zu  7344wzw35461x504
    2   xvutrv84xvutrvvu  1354u89rc3z42zv6  29u2v165a3w0sxxr  328uw561byxvua1x  ay30z47v6912v774  avww6avyxv4u6w52
    3   x3uvrvurxv9w22v4  y90841z529z72vvr  5wy3rw7t9a58u726  0avuvz9r20u5wz0v  31y4367vaa30tvu1  2v9045633y70wax4
    4   8wutrvuw07y2vzys  67x2192x929t3404  3yuvrau00775u302  y0084vysc96ztw4w  511v5awty9905wz1  6223s0zz9w8236ux
    5   2z014984267uw0wu  xau8668t0w5vvv4w  0y281wys24v5wvvv  76zwxw16008tyw36  9y0wxx8t873xt1vr  8064z6913746t4u3
    6   0wu5v7xwyzyvs09v  caz5u75x6927r87r  x44y165r49y7ww71  13yvs9160w546666  b663yyvx77w137x5  cy9y2xz602u55vvt
    7   1vu6t42sx941zvu1  98u8336y7azzv926  za51svvv7y6t4494  977y50vv5a2yy9wx  46676y40x2x559vu  9y9542uvc3v5x91y
    8   axutr0zrxvuy6v66  z41x63yr1y23r13x  289zr91yy130z44w  9wvxza30935wz74w  54xy26vta0yww4ww  62970z35x22wuxwu
    9   0ax0uv104y1w0x7x  6z7ys1337611xx0w  8zyts8yt644uwv7v  x70222x3b13t14zu  2w02uyyy651u2w4x  y505wv8s29v3r53v
    10  76665954261v632u  y560y4xs871wuxyr  x78xy11r53y5zvz1  zv8wt08ux83wua66  9a8w4x4z068uuw5v  b4y3z49xzxwvvw9t
    11  6285455t07v3345t  9y1t406z2123z06t  05943ywx27v6s98y  29yx2x3r8ww55x1s  x5vy2z155828ux62  c47z3y45b632x493
    12  y7u7sa1ub80t5895  5360wy4wxvu3t702  619wr51tzvw5w11x  x247r61z07zy1auz  ay68s5v5620wyyx4  xx860a1vav933a6z
    13  c9171572a674468s  y51xrvxw2x60uw6v  4z15w37xx8ztrzuw  9wvy174tcxu7swxv  zw9w231356u6z211  25utrvurxvy2v0y5
    14  9a9zyww4b89y60vw  yy36329s0780t80u  1zy3za6115vvt324  cz6xx4w15913y1w2  5174t99t7a45s43y                  
    15  9612y51185z1vxvu  83xxy1zr5xw1y423  48u1w236137xuy0y  axy8040rz43u3xus  1v3yr53r2wwuy3u6                  
    16  9y38y1xs6wz30835  b0uxs9uyx497s134  1538u8405508saww  650009760737485t  4355z3yz1w45xx96                  
    17  6a38xa0539x3u1yr  6wzz54w20zw84225  8332325t15w0188s  721107uy617w3674  9wu8t3z52xu2swyw                  
    18  9a744672z68wuwvz  zw2vszu41yv54003  z7y7tax127u16vv3  3046089uy39zs9v3  z665v0ys07zx439x                  
    19  578y27568a48yz2x  xx9x52xs911y56vu  660yx1vyya7xy54y  xwx6200r6wwx3z00  76v6u86384953yzy                  
    20  z12z060za602y66x  x476u3333v4v460y  4355wzw328185vw4  49874z7415v7u28s  6643w62y654y41v0                  
    21  47w20w515612y31z  b9w05x8uyw52r6y2  xxu04y3s3207u753  852t322ub142z07x  155z2zyv247v316u                  
    22  3373vvxzc93w3vy0  byw425x160y4s962  901tx20y844034uy  b91u453u55wzzavw  966xv5725968yv45                  
    23  7935v94yx86yrx7r  25z327426x16v6v2  a760051rz82632zv  9300y473zzvvyw9x  4vvyv2vx612yz9vt                  
    24  1861426y4v16v38u  0z40vv1ua66t012v  8xz5ta8u707wzv5s  6xuyry610448034w  1y863990x91vs1w5                  
    25  2701638r7a8tz86y  xy44u81400203a2s  0yx1rax113w42wx6  93zxw97s4www64zr  5866swzs7a6vyz3v                  
    26  by9uw6uv65yyvz71  y62xsaxx7a9y19vs  b20z0z8xxy40v75r  017yu91097ww5v1z  7a34241t2zztw910                  
    27  69605v7r009u03y0  x6vtrxu68z6t6v33  53y1xz16x3ux523v  05w7sa2v213632zs  4a92xy408vw0534y                  
    28  90wzrxxyb2xur0ux  2y8xy4ws2a04sz2x  831xz0837v72r1v3  9x71v74rz128661r  b52u0z5167w4169w                  
    29  712zxz4x4714y21y  9v36ra2s0vv2s4zt  y3v51v3u69yw2343  788x2w92544zxv2s  18wvt4z0a2vwx1x2                  
    30  8218s9w6zx7vw09s  62u7w7z11xx8s9zu  89213234668ur61z  1a4ww7544vzts993  b294u715c2z4wv56                  
    31  c3082z6y926060y0  5w6txy8zzvvz256w  2723t0u2cy836z61  c98uzx537x582wx2  623zw63v820ys3wz                  



```python
def coset_graph(t, n, alphabet=alpha, cosets=[]):
    la = len(alphabet)
    lt = len(t)
    for i in range(n):
        if len(cosets) > 0 and i not in cosets:
            continue
        cst = t[i::n]
        ctr = dict(Counter(cst))
        counts = [0]*la
        for a in range(la):
            if alphabet[a] in ctr:
                counts[a] = ctr[alphabet[a]] / lt
        plt.plot(range(la), counts, label=f'coset {i}')
        plt.vlines([3, 16], 0, max(counts))
    #plt.legend()
    plt.show()
```


```python
coset_graph(ct, 32, alpha)
```


![png](output_27_0.png)



```python
coset_graph(ct, 24, alpha)
```


![png](output_28_0.png)



```python
coset_graph(ct, 16, alpha)
```


![png](output_29_0.png)



```python
coset_graph(ct, 8, alpha)
```


![png](output_30_0.png)



```python
coset_graph(ct, 4, alpha)
```


![png](output_31_0.png)



```python
coset_graph(ct, 2, alpha)
```


![png](output_32_0.png)



```python
coset_graph(ct, 8, alpha, [0, 1])
```


![png](output_33_0.png)



```python
coset_graph(devig(ct, 'uuuuuuuu'), 8, alpha, [5])
```


![png](output_34_0.png)



```python
coset_graph(ct, 16, alpha, [0, 1])
```


![png](output_35_0.png)



```python
friedman(ct), friedman(ct1), friedman(ct2)
```




    ((0.05340711426792772, 1.7195215721453774),
     (0.05361878606018217, 1.6957902151387798),
     (0.05438075450258741, 1.6170017330410213))




```python
ct[::16]
```




    '5xxx8201a076yc999695z43712b6978c9c1y6xc9z6y95yy8b6zxxbb20xyx2965112530xz28x0641418z64x9a80b58y821c30y7199xz2x9ca673x48b96900971c4aa359b4529xaz5149z761941574b1b627a268c96ybcx21'




```python
from statistics import mean
def coset_test(t, n):
    return mean([friedman(t[c::n])[0] for c in range(n)])
```


```python
d = {}
for i in range(1, 33):
    d[i] = coset_test(ct, i)
d
```




    {1: 0.05340711426792772,
     2: 0.05399977028138479,
     3: 0.05337997724016072,
     4: 0.058101079133967955,
     5: 0.053169951328692094,
     6: 0.05385646797718866,
     7: 0.053132301320422376,
     8: 0.06277003025298648,
     9: 0.053784998676506726,
     10: 0.05373144802130646,
     11: 0.05350822343757516,
     12: 0.057767186975785464,
     13: 0.053116469648087083,
     14: 0.05371917306590673,
     15: 0.053027241490239595,
     16: 0.06255414922596506,
     17: 0.053485431281595386,
     18: 0.05432697529471723,
     19: 0.052134024170279195,
     20: 0.05771266216840192,
     21: 0.05332425526567598,
     22: 0.05413527854472736,
     23: 0.05445572160404014,
     24: 0.06230052708688391,
     25: 0.05291119691119691,
     26: 0.05346954390332983,
     27: 0.05417973069791079,
     28: 0.057674264510999204,
     29: 0.0532250796739449,
     30: 0.053433532604551075,
     31: 0.052755218684903356,
     32: 0.06195816930329761}




```python
cosplit(devig(ct, 'aaaaaaaa'), 8)
```

              0         1         2         3         4         5         6         7         8         9         10
    0   54ztv9yy  9y38y1xs  9077y363  b0uxs9uy  102w173z  1538u840  1w2w446r  65000976  4z58v63u  4355z3yz  2vxtuwwx
    1   x8u3s5u1  6wz30835  y79xz26y  x497s134  96u5u5yr  5508saww  1x5vv5yu  0737485t  89yyx146  1w45xx96  x396y0yy
    2   xvutrvu4  6a38xa05  cavuzavs  6wzz54w2  1y47330y  8332325t  cvxzuv03  721107uy  ax670304  9wu8t3z5  7344wzw3
    3   14y1vzzt  39x3u1yr  bv5usw06  0zw84225  4wvw1vwy  15w0188s  978ws79z  617w3674  6v2858zu  2xu2swyw  5461x504
    4   xvutrv84  9a744672  1354u89r  zw2vszu4  29u2v165  z7y7tax1  328uw561  3046089u  ay30z47v  z665v0ys  avww6avy
    5   xvutrvvu  z68wuwvz  c3z42zv6  1yv54003  a3w0sxxr  27u16vv3  byxvua1x  y39zs9v3  6912v774  07zx439x  xv4u6w52
    6   x3uvrvur  578y2756  y90841z5  xx9x52xs  5wy3rw7t  660yx1vy  0avuvz9r  xwx6200r  31y4367v  76v6u863  2v904563
    7   xv9w22v4  8a48yz2x  29z72vvr  911y56vu  9a58u726  ya7xy54y  20u5wz0v  6wwx3z00  aa30tvu1  84953yzy  3y70wax4
    8   8wutrvuw  z12z060z  67x2192x  x476u333  3yuvrau0  4355wzw3  y0084vys  49874z74  511v5awt  6643w62y  6223s0zz
    9   07y2vzys  a602y66x  929t3404  3v4v460y  0775u302  28185vw4  c96ztw4w  15v7u28s  y9905wz1  654y41v0  9w8236ux
    10  2z014984  47w20w51  xau8668t  b9w05x8u  0y281wys  xxu04y3s  76zwxw16  852t322u  9y0wxx8t  155z2zyv  8064z691
    11  267uw0wu  5612y31z  0w5vvv4w  yw52r6y2  24v5wvvv  3207u753  008tyw36  b142z07x  873xt1vr  247v316u  3746t4u3
    12  0wu5v7xw  3373vvxz  caz5u75x  byw425x1  x44y165r  901tx20y  13yvs916  b91u453u  b663yyvx  966xv572  cy9y2xz6
    13  yzyvs09v  c93w3vy0  6927r87r  60y4s962  49y7ww71  844034uy  0w546666  55wzzavw  77w137x5  5968yv45  02u55vvt
    14  1vu6t42s  7935v94y  98u8336y  25z32742  za51svvv  a760051r  977y50vv  9300y473  46676y40  4vvyv2vx  9y9542uv
    15  x941zvu1  x86yrx7r  7azzv926  6x16v6v2  7y6t4494  z82632zv  5a2yy9wx  zzvvyw9x  x2x559vu  612yz9vt  c3v5x91y
    16  axutr0zr  1861426y  z41x63yr  0z40vv1u  289zr91y  8xz5ta8u  9wvxza30  6xuyry61  54xy26vt  1y863990  62970z35
    17  xvuy6v66  4v16v38u  1y23r13x  a66t012v  y130z44w  707wzv5s  935wz74w  0448034w  a0yww4ww  x91vs1w5  x22wuxwu
    18  0ax0uv10  2701638r  6z7ys133  xy44u814  8zyts8yt  0yx1rax1  x70222x3  93zxw97s  2w02uyyy  5866swzs  y505wv8s
    19  4y1w0x7x  7a8tz86y  7611xx0w  00203a2s  644uwv7v  13w42wx6  b13t14zu  4www64zr  651u2w4x  7a6vyz3v  29v3r53v
    20  76665954  by9uw6uv  y560y4xs  y62xsaxx  x78xy11r  b20z0z8x  zv8wt08u  017yu910  9a8w4x4z  7a34241t  b4y3z49x
    21  261v632u  65yyvz71  871wuxyr  7a9y19vs  53y5zvz1  xy40v75r  x83wua66  97ww5v1z  068uuw5v  2zztw910  zxwvvw9t
    22  6285455t  69605v7r  9y1t406z  x6vtrxu6  05943ywx  53y1xz16  29yx2x3r  05w7sa2v  x5vy2z15  4a92xy40  c47z3y45
    23  07v3345t  009u03y0  2123z06t  8z6t6v33  27v6s98y  x3ux523v  8ww55x1s  213632zs  5828ux62  8vw0534y  b632x493
    24  y7u7sa1u  90wzrxxy  5360wy4w  2y8xy4ws  619wr51t  831xz083  x247r61z  9x71v74r  ay68s5v5  b52u0z51  xx860a1v
    25  b80t5895  b2xur0ux  xvu3t702  2a04sz2x  zvw5w11x  7v72r1v3  07zy1auz  z128661r  620wyyx4  67w4169w  av933a6z
    26  c9171572  712zxz4x  y51xrvxw  9v36ra2s  4z15w37x  y3v51v3u  9wvy174t  788x2w92  zw9w2313  18wvt4z0  25utrvur
    27  a674468s  4714y21y  2x60uw6v  0vv2s4zt  x8ztrzuw  69yw2343  cxu7swxv  544zxv2s  56u6z211  a2vwx1x2  xvy2v0y5
    28  9a9zyww4  8218s9w6  yy36329s  62u7w7z1  1zy3za61  89213234  cz6xx4w1  1a4ww754  5174t99t  b294u715  1z47vx0r
    29  b89y60vw  zx7vw09s  0780t80u  1xx8s9zu  15vvt324  668ur61z  5913y1w2  4vzts993  7a45s43y  c2z4wv56          
    30  9612y511  c3082z6y  83xxy1zr  5w6txy8z  48u1w236  2723t0u2  axy8040r  c98uzx53  1v3yr53r  623zw63v          
    31  85z1vxvu  926060y0  5xw1y423  zvvz256w  137xuy0y  cy836z61  z43u3xus  7x582wx2  2wwuy3u6  820ys3wz          



```python
coset(ct, 8)
```

    Coset 0: 0123456789abcxyz
    x 0.012168933428775949
    6 0.01145311381531854
    9 0.010737294201861132
    2 0.010379384395132427
    1 0.009305654974946313
    0 0.009305654974946313
    5 0.0082319255547602
    8 0.007516105941302791
    7 0.0071581961345740875
    b 0.006442376521116679
    4 0.006084466714387974
    z 0.006084466714387974
    y 0.00572655690765927
    c 0.00572655690765927
    a 0.005368647100930566
    3 0.0035790980672870437
    Coset 1: 0123456789avwxyz
    7 0.010379384395132427
    v 0.010021474588403722
    3 0.009305654974946313
    9 0.009305654974946313
    6 0.00894774516821761
    y 0.00894774516821761
    w 0.008589835361488905
    a 0.008589835361488905
    2 0.007874015748031496
    5 0.007874015748031496
    x 0.0071581961345740875
    4 0.006442376521116679
    8 0.00572655690765927
    1 0.00572655690765927
    0 0.005368647100930566
    z 0.005010737294201861
    Coset 2: 0123456789uvwxyz
    u 0.011095204008589835
    1 0.009305654974946313
    6 0.009305654974946313
    9 0.00894774516821761
    4 0.008589835361488905
    2 0.0082319255547602
    w 0.0082319255547602
    v 0.007874015748031496
    y 0.007516105941302791
    7 0.007516105941302791
    8 0.007516105941302791
    3 0.007516105941302791
    0 0.0071581961345740875
    z 0.006442376521116679
    5 0.005010737294201861
    x 0.0046528274874731565
    Coset 3: 012345678tuvwxyz
    w 0.010021474588403722
    5 0.009305654974946313
    8 0.009305654974946313
    t 0.00894774516821761
    y 0.00894774516821761
    0 0.00894774516821761
    x 0.007874015748031496
    7 0.007516105941302791
    3 0.0071581961345740875
    2 0.0071581961345740875
    4 0.0071581961345740875
    v 0.006800286327845383
    6 0.006800286327845383
    1 0.006442376521116679
    u 0.006442376521116679
    z 0.006084466714387974
    Coset 4: 0123456rstuvwxyz
    s 0.01145311381531854
    r 0.010021474588403722
    u 0.009663564781675018
    v 0.009305654974946313
    3 0.00894774516821761
    y 0.00894774516821761
    w 0.008589835361488905
    2 0.007874015748031496
    4 0.007874015748031496
    z 0.007516105941302791
    5 0.006442376521116679
    x 0.006442376521116679
    0 0.006084466714387974
    6 0.00572655690765927
    t 0.005368647100930566
    1 0.0046528274874731565
    Coset 5: 0123456789avwxyz
    v 0.012526843235504653
    9 0.009305654974946313
    4 0.00894774516821761
    z 0.008589835361488905
    6 0.008589835361488905
    w 0.008589835361488905
    3 0.0082319255547602
    a 0.0082319255547602
    2 0.0071581961345740875
    0 0.0071581961345740875
    x 0.0071581961345740875
    1 0.0071581961345740875
    5 0.006800286327845383
    7 0.006800286327845383
    8 0.005010737294201861
    y 0.0046528274874731565
    Coset 6: 0123456789uvwxyz
    1 0.010737294201861132
    v 0.010379384395132427
    6 0.009305654974946313
    u 0.0082319255547602
    3 0.0082319255547602
    4 0.007874015748031496
    y 0.007516105941302791
    9 0.007516105941302791
    7 0.007516105941302791
    0 0.007516105941302791
    z 0.0071581961345740875
    w 0.0071581961345740875
    x 0.0071581961345740875
    5 0.006442376521116679
    8 0.006084466714387974
    2 0.006084466714387974
    Coset 7: 0123456rstuvwxyz
    r 0.010737294201861132
    y 0.010379384395132427
    s 0.009663564781675018
    x 0.00894774516821761
    u 0.008589835361488905
    3 0.008589835361488905
    4 0.007874015748031496
    v 0.007874015748031496
    6 0.007874015748031496
    1 0.007516105941302791
    t 0.0071581961345740875
    w 0.006442376521116679
    2 0.006084466714387974
    z 0.006084466714387974
    5 0.00572655690765927
    0 0.005368647100930566



```python
# nopqrstuvwx lmnopqrstuv klmnopqrstu jklmnopqrst hijklmnopqr lmnopqrstuv klmnopqrstu hijklmnopqr
url = devig(ct, 'tvushsun', ac=False)
#print(bitly(url))
for i in range(8, 160, 8):
    print(url[i-8:i])
```

    mjfborel
    enallnao
    eaabkdar
    ijejohfg
    eaabkdor
    eaabkdbh
    eiadkdae
    eapevkbr
    pbabkdaj
    hmekohef
    jegjxror
    jlncpich
    hbanopdj
    feedlipi
    iaaommif
    eokjsdao
    rcabkife
    eaagzdmt
    hpdindhn



```python
url = devig(''.join(alpha), 'hirsch')
bitly(url), url
```




    (<Response [404]>, '33vvc89911ieff77oklldduqrrjj0wxxpp62')




```python
rules = {
    0: [('x', 'e'), ('6', 't')],
    1: [('7', 't'), ('v', 't')],
    2: [('u', 'e'), ('1', 't')],
    3: [('w', 'e'), ('5', 't')],
    4: [('s', 'e'), ('r', 't')],
    5: [('v', 'e'), ('9', 't')],
    6: [('1', 'a'), ('v', 't')],
    7: [('r', 'e'), ('y', 't')],
}
```


```python
for k, v in rules.items():
    src, e = v[0]
    print(k, devig(src, e))
```

    0 t
    1 o
    2 q
    3 s
    4 o
    5 r
    6 1
    7 n



```python
# nopqrstuvwx lmnopqrstuv klmnopqrstu jklmnopqrst hijklmnopqr lmnopqrstuv klmnopqrstu hijklmnopqr
cosplit(ct, 16)
```

                       0                 1                 2                 3                 4                 5
    0   54ztv9yyx8u3s5u1  9077y363y79xz26y  102w173z96u5u5yr  1w2w446r1x5vv5yu  4z58v63u89yyx146  2vxtuwwxx396y0yy
    1   xvutrvu414y1vzzt  cavuzavsbv5usw06  1y47330y4wvw1vwy  cvxzuv03978ws79z  ax6703046v2858zu  7344wzw35461x504
    2   xvutrv84xvutrvvu  1354u89rc3z42zv6  29u2v165a3w0sxxr  328uw561byxvua1x  ay30z47v6912v774  avww6avyxv4u6w52
    3   x3uvrvurxv9w22v4  y90841z529z72vvr  5wy3rw7t9a58u726  0avuvz9r20u5wz0v  31y4367vaa30tvu1  2v9045633y70wax4
    4   8wutrvuw07y2vzys  67x2192x929t3404  3yuvrau00775u302  y0084vysc96ztw4w  511v5awty9905wz1  6223s0zz9w8236ux
    5   2z014984267uw0wu  xau8668t0w5vvv4w  0y281wys24v5wvvv  76zwxw16008tyw36  9y0wxx8t873xt1vr  8064z6913746t4u3
    6   0wu5v7xwyzyvs09v  caz5u75x6927r87r  x44y165r49y7ww71  13yvs9160w546666  b663yyvx77w137x5  cy9y2xz602u55vvt
    7   1vu6t42sx941zvu1  98u8336y7azzv926  za51svvv7y6t4494  977y50vv5a2yy9wx  46676y40x2x559vu  9y9542uvc3v5x91y
    8   axutr0zrxvuy6v66  z41x63yr1y23r13x  289zr91yy130z44w  9wvxza30935wz74w  54xy26vta0yww4ww  62970z35x22wuxwu
    9   0ax0uv104y1w0x7x  6z7ys1337611xx0w  8zyts8yt644uwv7v  x70222x3b13t14zu  2w02uyyy651u2w4x  y505wv8s29v3r53v
    10  76665954261v632u  y560y4xs871wuxyr  x78xy11r53y5zvz1  zv8wt08ux83wua66  9a8w4x4z068uuw5v  b4y3z49xzxwvvw9t
    11  6285455t07v3345t  9y1t406z2123z06t  05943ywx27v6s98y  29yx2x3r8ww55x1s  x5vy2z155828ux62  c47z3y45b632x493
    12  y7u7sa1ub80t5895  5360wy4wxvu3t702  619wr51tzvw5w11x  x247r61z07zy1auz  ay68s5v5620wyyx4  xx860a1vav933a6z
    13  c9171572a674468s  y51xrvxw2x60uw6v  4z15w37xx8ztrzuw  9wvy174tcxu7swxv  zw9w231356u6z211  25utrvurxvy2v0y5
    14  9a9zyww4b89y60vw  yy36329s0780t80u  1zy3za6115vvt324  cz6xx4w15913y1w2  5174t99t7a45s43y                  
    15  9612y51185z1vxvu  83xxy1zr5xw1y423  48u1w236137xuy0y  axy8040rz43u3xus  1v3yr53r2wwuy3u6                  
    16  9y38y1xs6wz30835  b0uxs9uyx497s134  1538u8405508saww  650009760737485t  4355z3yz1w45xx96                  
    17  6a38xa0539x3u1yr  6wzz54w20zw84225  8332325t15w0188s  721107uy617w3674  9wu8t3z52xu2swyw                  
    18  9a744672z68wuwvz  zw2vszu41yv54003  z7y7tax127u16vv3  3046089uy39zs9v3  z665v0ys07zx439x                  
    19  578y27568a48yz2x  xx9x52xs911y56vu  660yx1vyya7xy54y  xwx6200r6wwx3z00  76v6u86384953yzy                  
    20  z12z060za602y66x  x476u3333v4v460y  4355wzw328185vw4  49874z7415v7u28s  6643w62y654y41v0                  
    21  47w20w515612y31z  b9w05x8uyw52r6y2  xxu04y3s3207u753  852t322ub142z07x  155z2zyv247v316u                  
    22  3373vvxzc93w3vy0  byw425x160y4s962  901tx20y844034uy  b91u453u55wzzavw  966xv5725968yv45                  
    23  7935v94yx86yrx7r  25z327426x16v6v2  a760051rz82632zv  9300y473zzvvyw9x  4vvyv2vx612yz9vt                  
    24  1861426y4v16v38u  0z40vv1ua66t012v  8xz5ta8u707wzv5s  6xuyry610448034w  1y863990x91vs1w5                  
    25  2701638r7a8tz86y  xy44u81400203a2s  0yx1rax113w42wx6  93zxw97s4www64zr  5866swzs7a6vyz3v                  
    26  by9uw6uv65yyvz71  y62xsaxx7a9y19vs  b20z0z8xxy40v75r  017yu91097ww5v1z  7a34241t2zztw910                  
    27  69605v7r009u03y0  x6vtrxu68z6t6v33  53y1xz16x3ux523v  05w7sa2v213632zs  4a92xy408vw0534y                  
    28  90wzrxxyb2xur0ux  2y8xy4ws2a04sz2x  831xz0837v72r1v3  9x71v74rz128661r  b52u0z5167w4169w                  
    29  712zxz4x4714y21y  9v36ra2s0vv2s4zt  y3v51v3u69yw2343  788x2w92544zxv2s  18wvt4z0a2vwx1x2                  
    30  8218s9w6zx7vw09s  62u7w7z11xx8s9zu  89213234668ur61z  1a4ww7544vzts993  b294u715c2z4wv56                  
    31  c3082z6y926060y0  5w6txy8zzvvz256w  2723t0u2cy836z61  c98uzx537x582wx2  623zw63v820ys3wz                  



```python
base64.b64decode('toqsorln')
```




    b'\xb6\x8a\xac\xa2\xb9g'




```python
bitly(ct2)
```




    <Response [404]>




```python
def vsafe(c):
    r = c.lower()
    if '=' in r:
        r = r[:r.index('=')]
    return r
```


```python
key_opts = [
    #'dex64', 'flagdex64',
    b64en(':flag_de:x64'),
    b64en(':flag_de:'),
    b64en('flag_de'),
    b64en('dex64'),
    b64en('de'),
    b64en('deutschland'),
    #'hirsch',
    b64en('hirsch'),
    b64en('hcsrih'),
    b64en('46xed'),
    b64en('eksvierundsechzig'),
    b64en('xvierundsechzig'),
    #'de'*64,
    b64en('de'*64),
    #'flagde'*64,
    b64en('flagde'*64),
    b64en('flag_de'*64),
    b64en(':flag_de:'*64),
    #str(0xde * 0x64),
    #str(0xde * 64),
    b64en(str(0xde * 0x64)),
    b64en(str(0xde * 64)),
    #hex(0xde * 0x64)[2:],
    #hex(0xde * 64)[2:],
    b64en(hex(0xde * 0x64)),
    b64en(hex(0xde * 64)),
    b64en(hex(0xde * 0x64)[2:]),
    b64en(hex(0xde * 64)[2:]),
    #str(0xde ^ 0x64),
    #str(0xde ^ 64),
    b64en(str(0xde ^ 0x64)),
    b64en(str(0xde ^ 64)),
    #hex(0xde ^ 0x64)[2:],
    #hex(0xde ^ 64)[2:],
    b64en(hex(0xde ^ 0x64)[2:]),
    b64en(hex(0xde ^ 64)[2:])
]
```

## Task 1 solution


```python
devig(oxedit3, b64en(':flag_de:').lower())
```




    'alleswasdubrauchs7iseinetasseetwasmehlfll5tduhineinirgendw4sseskommthinzuundauchetwassalzdarfdab3iseindazue1nlffelvanilleundrhr5umundlassessackenfgewasduwillsnochd4zuunddannw1rddasganzeschngebacken'




```python
sol1 = 'alleswasdubrauchs7iseinetasseetwasmehlfüll5tduhineinirgendw4ssüβeskommthinzuundauchetwassalzdarfdab3iseindazue1nlöffelvanilleundrühr5umundlassessackenfügewasduwillsnochd4zuunddannw1rddasganzeschöngebacken'
sol2 = 'alles was du brauchs7 is eine tasse etwas mehl füll5t du hinein irgendw4ssüβeskommthinzuundauchetwassalzdarfdab3iseindazue1nlöffelvanilleundrühr5umundlassessackenfügewasduwillsnochd4zuunddannw1rddasganzeschöngebacken'
sol1
```




    'alleswasdubrauchs7iseinetasseetwasmehlfüll5tduhineinirgendw4ssüβeskommthinzuundauchetwassalzdarfdab3iseindazue1nlöffelvanilleundrühr5umundlassessackenfügewasduwillsnochd4zuunddannw1rddasganzeschöngebacken'




```python
def caesar(t, n, alphabet=alpha):
    n = n % len(alphabet)
    return envig(t, alphabet[n], alphabet=alphabet)
```


```python
rules = {
    '1': 'I',
    '3': 'E',
    '4': 'A',
    '5': 'S',
    '7': 'T',
}
def subst(t, rules={}):
    return ''.join([rules[c] if c in rules else c for c in t])
```


```python
for i in range(36):
    continue
    print(caesar(subst(ct, rules).lower(), i), end='\n\n')
subst(ct, rules)
```




    'SAztv9yyx8uEsSuIxvutrvuAIAyIvzztxvutrv8AxvutrvvuxEuvrvurxv9w22vA8wutrvuw0Ty2vzys2z0IA98A26Tuw0wu0wuSvTxwyzyvs09vIvu6tA2sx9AIzvuIaxutr0zrxvuy6v660ax0uvI0AyIw0xTxT666S9SA26Iv6E2u628SASSt0TvEEAStyTuTsaIub80tS89Sc9ITIST2a6TAA68s9a9zywwAb89y60vw96I2ySII8SzIvxvu9yE8yIxs6wzE08ES6aE8xa0SE9xEuIyr9aTAA6T2z68wuwvzST8y2TS68aA8yz2xzI2z060za602y66xATw20wSIS6I2yEIzEETEvvxzc9EwEvy0T9ESv9Ayx86yrxTrI86IA26yAvI6vE8u2T0I6E8rTa8tz86yby9uw6uv6SyyvzTI6960SvTr009u0Ey090wzrxxyb2xur0uxTI2zxzAxATIAy2Iy82I8s9w6zxTvw09scE082z6y926060y090TTyE6EyT9xz26ycavuzavsbvSusw06IESAu89rcEzA2zv6y908AIzS29zT2vvr6Tx2I92x929tEA0Axau8668t0wSvvvAwcazSuTSx692Tr8Tr98u8EE6yTazzv926zAIx6EyrIy2ErIEx6zTysIEET6IIxx0wyS60yAxs8TIwuxyr9yItA06z2I2Ez06tSE60wyAwxvuEtT02ySIxrvxw2x60uw6vyyE6E29s0T80t80u8ExxyIzrSxwIyA2Eb0uxs9uyxA9TsIEA6wzzSAw20zw8A22Szw2vszuAIyvSA00Exx9xS2xs9IIyS6vuxAT6uEEEEvAvA60yb9w0Sx8uywS2r6y2bywA2SxI60yAs9622SzE2TA26xI6v6v20zA0vvIua66t0I2vxyAAu8IA0020Ea2sy62xsaxxTa9yI9vsx6vtrxu68z6t6vEE2y8xyAws2a0Asz2x9vE6ra2s0vv2sAzt62uTwTzIIxx8s9zuSw6txy8zzvvz2S6wI02wITEz96uSuSyrIyATEE0yAwvwIvwy29u2vI6SaEw0sxxrSwyErwTt9aS8uT26Eyuvrau00TTSuE020y28Iwys2AvSwvvvxAAyI6SrA9yTwwTIzaSIsvvvTy6tAA9A289zr9IyyIE0zAAw8zyts8yt6AAuwvTvxT8xyIIrSEySzvzI0S9AEywx2Tv6s98y6I9wrSItzvwSwIIxAzISwETxx8ztrzuwIzyEza6IISvvtE2AA8uIw2E6IETxuy0yISE8u8A0SS08saww8EE2E2StISw0I88szTyTtaxI2TuI6vvE660yxIvyyaTxySAyAESSwzwE28I8SvwAxxu0AyEsE20TuTSE90Itx20y8AA0EAuyaT600SIrz826E2zv8xzSta8uT0TwzvSs0yxIraxIIEwA2wx6b20z0z8xxyA0vTSrSEyIxzI6xEuxS2Ev8EIxz08ETvT2rIvEyEvSIvEu69yw2EAE892IE2EA668ur6Iz2T2Et0u2cy8E6z6IIw2wAA6rIxSvvSyucvxzuv0E9T8wsT9zE28uwS6IbyxvuaIx0avuvz9r20uSwz0vy008Avysc96ztwAwT6zwxwI6008tywE6IEyvs9I60wSA66669TTyS0vvSa2yy9wx9wvxzaE09ESwzTAwxT0222xEbIEtIAzuzv8wt08ux8Ewua6629yx2xEr8wwSSxIsx2ATr6Iz0TzyIauz9wvyITAtcxuTswxvcz6xxAwIS9IEyIw2axy80A0rzAEuExus6S0009T60TETA8StT2II0Tuy6ITwE6TAE0A6089uyE9zs9vExwx6200r6wwxEz00A98TAzTAISvTu28s8S2tE22ubIA2z0Txb9IuASEuSSwzzavw9E00yATEzzvvyw9x6xuyry6I0AA80EAw9Ezxw9TsAwww6Azr0ITyu9I09TwwSvIz0SwTsa2v2IE6E2zs9xTIvTArzI2866IrT88x2w92SAAzxv2sIaAwwTSAAvzts99Ec98uzxSETxS82wx2AzS8v6Eu89yyxIA6ax6T0E0A6v28S8zuayE0zATv69I2vTTAEIyAE6TvaaE0tvuISIIvSawty990SwzI9y0wxx8t8TExtIvrb66EyyvxTTwIETxSA66T6yA0x2xSS9vuSAxy26vta0ywwAww2w02uyyy6SIu2wAx9a8wAxAz068uuwSvxSvy2zISS828ux62ay68sSvS620wyyxAzw9w2EIES6u6z2IISITAt99tTaASsAEyIvEyrSEr2wwuyEu6AESSzEyzIwASxx969wu8tEzS2xu2swywz66Sv0ys0TzxAE9xT6v6u86E8A9SEyzy66AEw62y6SAyAIv0ISSz2zyv2ATvEI6u966xvST2S968yvASAvvyv2vx6I2yz9vtIy86E990x9IvsIwSS866swzsTa6vyzEvTaEA2AIt2zztw9I0Aa92xyA08vw0SEAybS2u0zSI6TwAI69wI8wvtAz0a2vwxIx2b29AuTISc2zAwvS662Ezw6Ev820ysEwz2vxtuwwxxE96y0yyTEAAwzwESA6IxS0Aavww6avyxvAu6wS22v90AS6EEyT0waxA622Es0zz9w82E6ux806Az69IETA6tAuEcy9y2xz602uSSvvt9y9SA2uvcEvSx9Iy629T0zESx22wuxwuyS0Swv8s29vErSEvbAyEzA9xzxwvvw9tcATzEyASb6E2xA9Exx860aIvav9EEa6z2Sutrvurxvy2v0ySIzATvx0rSx'




```python
subst(ct1, rules)
```




    'SzvyxusuxuruIyvzxurBxurvxurux92vBuru0yvy20AB2Tww0uvxyys9Iut2xAzuaurzxuGG0xuIAI0TTGSS2IG2GBAS0vESyusIb0S9cIITaTAB99ywb9Gv9IyIBzvv9EyxGz0EGEx0Exuy9TATzBuvSB2SBAy2z200a0yGAw0SSIyIETvxcEEyTEvAxGrTIGAGAIvB20GBTBzGb9wuGyvTGGST090y9wrxbxruT2xAAIyIBIswzTw9c02G9GGy9TyGy9zGcvzvbSs0ISu9cz2vy0Az2z2vGxI299E0xuGB0SvAczuSG2rT9uEGTzv2zIGyI2rEGTsETIx0yGyxBIuy9IAG22zGSGwAxut0yIrx2GuGyEE90Bt0BxyzSwy2busux9sEGzSw0wA2z2suIvA0x9Sx9ISvxTuEEAA0bwSBySrybw2xGysG2z2AGIvv0AvIaG02xAuI02E2y2sxT9IvxvruBGGE2Byw20s29Er20vszGuwzIxszSGxBzv2GI2IE9uuyIAE0AvIw2uvGawsxSyrT9Su2Euru0Tu002Iy2vwvxAISAywTzSsvTGA929rIyEzABysyGAwTxByISyzz09Ew2vsBG9rIzwwIAIwTxzruIyzGIvt2AuwEITu0IEuAS0swBEESIwIBzytx2uGvG0xvyTyAASww2ISwxuAEE0uS9Ix0BAEuaG0Iz2EzBztBTTzS0xrxIw2xb00BxAvSSyxIxuSEBIzBTTrvyvIEGy2AB2EEGBrI22tucBGGI2AGISvycxu09Bs9EBwGbxuI0vv92uw0y0AycGtATzxI0ByEIysI0SGG9TSvS2yw9vzE9SzAx02xbEIzzBtBxEuG2y2EBwSIxArI0zIu9vIAcusxcGxwSIyway00zEEuG00T0EASTI0uGTETEA09y9svxx20GwE0ABATIvuBB2E2bAzTbIAESwzv90yTzvy9GurG0A0A9zwTAwGz0TuI9wSI0ws22EEz9TvAz2GITB29SAx2IAwSAzs9cBzSTS2xASvEByxAaG00G2SzaEzTGIvTEyETaEtuSISwy9Sz90xBBEtvbGyvTwExAGGAxxSvSx2vayww20uyGI2A9BAA0BuSxv2IS2uGaGsvG0yxz92ISuzISTt9TAsEIErE2wyuASzyIAx99utz2usyzGvy0zA9TvuGB9EzGAw2GAAvIS2y2TEG9GvTSGyAAvvvG2zvIBE9xIswSGszTGyETE2I2zwIA9xABwSAb20SGwI9Iwtzavxxb9uIczwSGEwEB0sw2xuwx9yyTAwwSGx0awGvxAGS29AGETwxG2sz9BEuBGz9EAtuc92z0uSv99AucvxIG90Ex2uwy0wB2vrEbyz9zwv9cTEAbEx9xB0Ia9EG2uruxyvyIAv0S'




```python
subst(ct2, rules)
```




    'At9yBESIvtvAAIztvtvAvtvuEvvrvw2AwtvwT2zszI9AGu0uwSTwzv0vvGAs9IvIxt0rvyvGa0v0ywxxGG9AGvEu2SStTEAtTTauBtBS9TS2GAGsazwABy0wG2SISIxuyBIswEBSaBaS9EIraAG2GwwzTyTGaBzxIzGzG2GxT2wIG2EzEEvz9wv09S9yByxrBI2yvGEuTIEratByyuGvSyzI90vr0uE00zxy2u0xIzzxTA2y2B9Gxv0sEBzy20000TEETx2yauasvuwGEABrEAzG9BIS9TvrT29x2tAAaBGtwvvwaSTx9TBrBBEyaz9GAxEryEIxzyIEGIxwS0AsTwxryt0zIE0tE0ywvET2Sxvwx0wvyG2sT0BuExIrxIAE0x9yATIAwzA2zB2SwvzAyS0Exx2sIyGuAGEEvvGy90xuw2G2yASI0A92SET2xGG2z0vuGtIvyABA00asGxaxay9sGtxGztvEyxAsaAzxvGasv2At2TTIxB9uwtyzvzSw0wTzGSSryTEywwvy92ISE0xrwEwtaBTGyva0TSE2yBwsASvvAyGr9TwIaIvvytAABz9yI0AwztBtAuvvTxIrESvISAyxTG9yIwStvSIxzSExBtzwzEaISvEABI2GExyySBB0SBawE22tS0BsTTaITIvEGyIyaxSyESzEBBvAx0ys2TTE0t2yA0AyT0SrBG2vxSau0wvsyIaIEAwG2zzxy0TrEIzGEx2vEx0Ev2IEESvu9wEE9I2AGuGzTE02yEzIwwArxvSuvzvETwTz2uSIyvaxauzr0Szv0Bvs9zwwGwwG0twGEv9GwAGGTy0vay9xwxa0EwTwT22EItAuvw0uBwaG9xxrwSxs2TGzTyazwyTtxTwvzxAI9EI2xBArAuxsS09GTTBt2ITyIwGA0GBuEz9EwG0rwxz09TzAST2sSt2uI20x9uSuSzawE0AEzvwxxyyIABEwEx9swwArIy90TwvzSTavIG2sxITrIBGrBxw2AzvsawTAvt9E9uxExBw2zBGu9yIGxTEAvBBuy0Av92TAIAGva0vIIvat90wIywxtTxIrGEyxTITSGTy02S9uAyGt0wAww2yySuwxawxzGuwvSyzSBBx2yBSS2wyAwwEEGG2IIA9taSAyvySrwuEGESEzwSxGwBESx2wwGS0sTxExGGBEASyyGEGySyI0SzzvAvIuGxS29BvSvy2xIy9tyG909vISBGwsavzvaAAtzt90a2y0v0EySuzITAGwBvA02wI22ATS2AvG2zGv2yEzvtwxEG0yEAzEAISAvwayvuw2v0SEy0aA2E0zw2Gx0AGITGAEyyxG2SvtyS2vES9y2TzS2wxuSSvs9ESvAEAxxvwtAzySG2AExGavvEazStvrv20SzTxrx'




```python
devig(ct, '75431541')
```




    '89504e470d0a1a0a0000000d49484452000000ed000000130802000000f3b71db10000053c4944415468deed5bd15523310c4c35144215f4400d29810ea8800ad20005500005f0cf3f373079737392d6abcdeebd5b72f88397ecdab23c1ac9b21c0e1f73ed60edfefe7eaadbdbdbdbe1cff6712dedf5f515cb797a7aba584213c39f7631915a9d9e9f9f6f6e6e3a3640cfdbdbdb2be331188ce5bcbfbfaf748626869b68db697bc67c2991ba8b79787868da4038fe93c049ae9c4ea70dc502d04dc8d7c7707d48e35c68f8e0afe08dc7e3f15b049a4544da9ec7e0d035f19849c5260237e7310506a68664a67c7b7777b77f1e2f22d255f1f86fb4c7c7c7f549c5de78cc1cf487c7ff118f11e0b1116f48bb3df0f85bb41f1e6fd65e5e5eb0109c39ae86c7f0c96d0f0ffbe231b240a5ff5c3cb69e8e0dd0cd0fc8c7af564e8f2974f840438a069694d5169cab7862651ac77931bc733240c370d5c8568a85c288c753a5000a2c6b1a74003552c731c4139dc7f13ce72d63b83476508228798ce5041e0709fe169d9156e92b342fd78e2182140d431cd56c02f4e731c675eb1309dd389c60a2db67ee27e2e311b90b4be32bba3a954b1ecb5a5abcab927d4b1b34a74073dbc0968403ab3d7d3587cf811b841f36aff5ae110b10020fb4c0f09c53e479215f6b1486c09d0f8130191952970e5c5a423f1e5381c063e82016bac54583ac98cb0c3a4043aec8677113a0275e0946ced8271230814a01d2cfbf3c8f63020f093cdc386b338fa141591c501409a5abb07e4e51da2fb81014a3c0d9fd5df60e77169789a5b4401d4299a150d40ce47670884c805a3afbc3265c1d1ee796f30a72202c5676747c58d60d500405444a8fca4a12288d7d08579f48d433674a9f3da98a6f1f25b899c7b24a27ade12c4e2f3a5c08f01c9b6566171fd47aa778bc542c5d7fe02d0207d391676e3cbcc5706767b9a7c907dcc79a702d8dc754b25c2fe3a5d380b133380f3a482bb13fe76694e603a74cb08848647f0804e794b87485eca0d9061c181ca0939e43b8acbe88c79d9be10b785c8a250bf3eaf4ca4183d9c042b24a43f036306ccce31cf867e15acae3323f763f1144f0550c5464156fd041fec621a5ab53617f35e0719f48421e7f31bbfbcfccd5e5148f857e26c1148f99c8b38ca50c69b73ce690a95320e325e30d933fcf5e44b290b12ce27107ae0b783c55af08c115aca2f20e1134f4c4692a8e7a762bd24f99602991c2019a679edf3c9eddb2a7789c0796d3cbdd65ad9df318f61e1c013db5609124c4697eeed4dd4a1e37e1ba80c783e6a985d6ee71da938a268f15c86779dc241271f6920503ca39af98a5c8545ed17123f95036d53e79cc23e0783a2e1f84569dc751c2d84ca0268ffb70ade4b1fb89a660814fa35cbd70501efcfee182bca2bfb13b74bf4b93be4566afd2ce986d908fed53d39789d49e794cdd664bcbd4df97200a8672ef221ef7e15ac36362e2bc942610ebca7316ac28cc3e7bcef3a9073cee138935bb12d5435925516933479a71b1a6cfe3d2a83be131b40a15b47e8d8f32cbd3cf1a1e9763733d21f3b87c8b0d877a86db2ef2afac199740950a905121780f78bc884841ac62ffc10f285e520911452bcc45413c54d8f6ab1d3dccb9fcc3579baa5b879aa5d6194ab6b44459d2c6c3cbc44adb8ecf70ae7015471696858e1243edcef90e72162e8dcd1151afc27494af9bb97254505e797ff963a9b027e8a7ea8194ba9c2babf54d222959d713663be7fb3c7ef75b50bf97965b94b76518285030312608fd7547a8ab542c89c86a6dd023ff1700a1f1bb50f7dacc63d75f3d978a1558c1e9cb06b5cb8bfa6cad290cf3f5b25f370ce012c3fcd704f81c6e7797fe949e078332231a6c50e15e1a0a94e94a89f6222241f2f9d6c3aeeb9969fc02ed9f74d0facfc85a0000000049454e44ae426082'




```python
devig(ct, 'tsaeisai')
```




    'mmzpnryqequzknutedupjduwimyxnhzledupjd8wedupjdvmelurjdujed9sukvwpeupjduohpyynhykjh0xwr8wjo7qoiwmheu1npxofhyrki9nidu2lm2ker4xrdutrfupjizjeduuyd6yhsxwmd1slg1ssf7poo62xr5wjo1ryl2mnk81wn5lhpvzvm5lfpu3ks1msq0pxq9xtr13tn7uro70wo8kqs9vqewwsq9uyivoqo1yqn1tpnzxnfvmqg34qjxknezzsq3xns34ps0xkrxzmjyjqs70wo7ugo8smevrmp8uup5yps44qh2pgj2vso0rro0yqo6plpwyse5tmo1yql1rkl7zndxrtr3svdysor31nr4qeq6ujf7jiq6xwk6qld12nl8mjp0xyl8jos8prq6qsg9qoounnnyunh7tnr6wxd7jhi9qslysqiwvjfxqskxqjiupoj2vph4plp10qk1qpk14krwygf7roi9ktl04uh6qqk6wyiysqi73ql6vfp9trk6qtsvqrsvksd5qke0yil50mq9jtlz0uhvyfr04wjzxjrz3udvjnpxytr2pqk9pvm0wesu4yo8lhe5rnd4otsz1mp5pnr23jq7jqqu4vl6qoszvnr2ygm1tylyjig2zjj3pnh7ukj3voo1xpf0ofn6wqmxkpp1smfyjqg1pwi6rjj2zri6lml6wog4oeduzlp0ufn1tjdxojf6wme6nfg32vk9khp8wlq0mplxtqjzjmfwxqm2vsiutkruqem93kj3wnezvxmwuhhw4wk2xge2rkhuwigv1wi0vef9txkxkqj1uxovmem72ml3vkd4rwo0qsrwwxf8mfe5yjoyusgw0unxtniy0kr6ujnzzup4unf12novuhh4wnd1mro6psj2neg40mq1whi2wvs2kfo2tksxpos9utrvkeovpjfuyph6pyd3vjg8tqmwkjs00kh2pqd32js2khdvykmzlnku3opztifx4krzmme6ppg8rgdvvun6oii2stp3rqou1mnyjig43vl0qlevstdwqjruynj6xrlwwkfxjmeyzje7lqs54mp2ykgurjsushp71ml0uhg24teykjmv1odvnem4uto5jlry3oe7tgs5xkdvnog6pwm9wjq9vjr1qfj3wrm4ophypkqylnm4qod7nep8tqj1jmly1rdzthn90vgwpjpv2kr8qnj9sjn1lgdw1oj1plh11ol7peqzpjhuoihyzrs6tinvrll2wlquxok3yil7tmg0qin34mq4smn04kswopl3yvk5linwwtq8kgpy3lsxtjpuxydvvno0upjvqfs7tqn4qll51ohwvjq14xdwwefuwwg3kkk03mp5vqi1ppk0qpm4wvmuqrp6wsn1jgq22vkznpfz1ls8moi7srd5khgxxjsxtilw0uexysk0vsh8peg4wnp5jmlyxph1yelutxk3npl1tri8vod7yjjvvflv1td3mnrysul4vpr2xvk3wno8qjo1rjp2zliuutg8zyh6tie2swm6jif5rnnymtdxvmd0vqp8skp9rkk8qon6tsgxrms1phsvqnh9jjiu1oh0nfi04wdyktr6vle4ooozspe1yhi8pqe3yilyrkr1yhe50yo6yqp7uxivnms2uqrwpqevtrs3sql5srp4oep0yukxvsj3ptmzmgd8sli8meq3sms6yjrytuf3jpew1xf1kek43jo1rhpzutsurqevutp4ltfu3kexnth6tpmwtmr1zqjwurfy4sm0jgm3qvfuknn0wsr7yhp33wq5lok1xspuqnj7svo7wki42sq9mfl9vkrvveex2ui0jnewtvh0slr83wh7winv3mk8kpn2pvk2msj4yri7psr1qwn3mmnwvrsvoql0wqm7vghvrqe9pnfuujg6thm44sl4oqlztor7klewsymzjhj7umr1sqpwsxd1rhnw3ks2njj32vkzkqf7xnp4jgj24yo1joq8tue9umm4vpd2kis4sop5wldzpkr9vtr8qrf5vof54uexulh54no3mpryupj4yrf63sl0wnd24xqzmrg3wrm7nnr1ynp7wkjy0vo7nrs3wldutmj1rxswlfr9wxeztqg0spf8lpp3tljvjso6zqgvpopwxvpxxlo63yg4sekx1xrvmmmxuuovlriysomwoje0ymgyqnn1que4pqs8swf4rho8qme5nenvuuh1xmq24mf6urg64knvxnk0sqgxwge9sul1vmou2rk1tmj70lr9los41km3qid3ujn3jjewqqluyll51rlyrie41pf9yqeu4llzxjfuykeyogo61niykhpztwl9poov2mq6vpm91vgzqno4zoo2qnn4uwjvsin5vuhynjm7rvj6mqo6tnn7umr64qd4xldvunkvpnj2urrvlig82vr9ser1rkjwxmq62kezkos6rqh3nos30um1ljhzpor1sls9ypg4spdwwxl4qsn2qsh5tnpw0to9oiqwrlmzsrkvspjxusk90mp1xtkz0od5ynk3voo3npk0uklwrjdxpmewpel92qiyqol40ohwvmm6xpn0wrdwsysvqed4qye5ujd9wwn6vkg7wosxwnk2zkizrqe8yvouppi60ro9tkp42lmuvtg9uufzyhku1xdvlqg91wkuntlv1pr1qnk93sh3xek2smfwmfn01od8kjrvzjn3nsmyzrm9pgfwrne9ltm7vvg4xso3ypm9vef82ss1nrd9zvs6rjnupjdujedyyniyxih43nf0jmf'




```python
def lel(data):
    ci, oi = -1, 0
    opt = [7, 5, 4, 3, 1, 5, 4, 1]
    #opt = [75, 43, 15, 41]
    out = []
    while ci < len(data):
        ci += opt[oi]
        oi = (oi + 1) % len(opt)
        if ci < len(data):
            out.append(data[ci])
    return out
''.join(lel(sol1))
```




    'arhisteehlunegw4khudatsadsduefvanrulasenslod4dnwgsnba'




```python
b64en(':flag_de:').lower()
```




    'omzsywdfzgu6'




```python
devig(subst(ct, rules).lower(), 'omzsywdfzgu6')
```




    'eyab7nvt82aieg5099ro2pae4y907dwo8paxdjjs99ro2pbyj25d39rm8pp0oq6skaro2pa0mh9k7dvndtgmwxjsekqp7ucymk5a77ur9tezeokdu9r144iwjxl0b9rdlraxdoa999rthpmamy8i69fvlsy0ml4f5k31338eoutdiszphwowwg3bc7s9p48xkh5b4ofpm2gxewkaonfotm96wu4smk5nk4p3kk7snm6thub0vutka6fdjmfmhl6clcb39cdwskawcmbnh4ucjybaqnu95cevvy4smkqxa0o0gk6h475tdn8auylqadzsaci3mubhmkxx90m1wh7kcapd30y6k2thqsq96pd3yxpeq9vv43uwhxlg9m3t2r9v4wh0mg3tlpyah2jce7xdh8ovfyjbbm3tmspyiu5di6vt6t9msxhi49qmbupym29iletu2rd2xq8c3ers4ci3jnlfm7f59wy2uqtq4nt1ar9ziokaosx3dtm2vqhiievvku9xk2hwa76sawm2yy6cbosnmp8yekbousp552pvy2aseds193gcw6aaenwodpbvsh8kunzskwpx0ybs9or3h0oxmk3d797rn4fwgh3finzo229vvw5qqs3t44f3hxdobofsh8ev4mdw3wbsht92e6pw5kfd8rg0kghiaounjny0gl99lcfolum3o6dwbe3o38m4imle99r94ng6kgtf39urdrm4gkhdacb1pwpwmhji5mxpj8d1k6a94btd94iixo5f4nrt84pxe6psiawu34c6mn7qmgznaqizen5sucsnlugijlkf4gunkcy2eu6c9oq158ui0jldmkxtm3c4eljcaapx20e6xm7se6udhueeexhke6w9dnq6slto7ksxbtq4hjtcmk3obcizjmls6mf5bui40ydaakzs34d1fykgunsn80bxdl5okd3ohpuiomjfaotnd4geendfl9b124iwmj6k4owohwaxiha0ubu333fyekhb9c5uapb3ogheuezrtnu3vu5a66vmtsqx02bgmasrtpc2ox5k7w3nl8c4el894av92q9xvy3q67z1psazdy5ic7qn58g6mmdquavnd4bwij6d9o7tt08vwx9b8aqda48mej6d5c3ol4peowkh3nft9cu4lylekdvo32exsylc89qq8no1k6t94svnapfmmgksqctsdnbaexjgiw6r2myxlj7a8wfsltywi24f9mwo2ta04n9wbo3dtmbzf2dsmmrd7wua424f6cxttmucgwli46x334c0u2pkqgpotmc44wjab7vo44dmoh50i9s9h0g2j66gaoqs9mq2w23a8dt9d2ycej7s9brvlsuw0qbb67p9kuyxjqbgko7vp4a2whhic6fma2ia0qadkbwn44oyfo4eb9pnbsdmdy80ust5dqdaxqbhcd5s8sq4hh394svd8tyaj25f4gbqj8y1lojw59qx2cbik26au9bph3e0o2lwknzdpwuesujc3kfudniifo5koc59htmm4kdemo3mtr8zhg9co9uu5pgivhje476upwoyigh0ncuq54y1my6c7d6mduawinbdaex3lpewyxhh5a7r40f0jktoce5o9qua429d4nf1bq8esuhol7qt3ubzeydgantskqb1lypilspranq0jhbkegu9mcux4yacb95r4uoyjwpe6o31d3e1olp9katn3rywjqlb3kfubnf24y5hlasttnqxyl5b4auqntm1jy704nf99cc6wl9qcoxma4uy0l5ai6xvb39amhpbmmpo4wymmh5giwqrp09e0olocm6p98p3ex6w9au1dugvsk7fqdxvl3oxwn4su6so5wowugdbqgzpmcq6lo4fnnfplmuyeg7hbosrk8g4ky4wbdsq9qp1sl5g3c3db4qcm2lelsws739wwk7eiowmbc92gxtil7tr3py3mg7b4ozqdcua0qaalbqd6nqvl6dqikfm42o1okkk4o7u8piw4yle87p5lpfxexkwon5par8ifl3qeauxlt8chupcknvt8cqawlhbcsx5hpicewacmcbva49zsxtk77q5pcee0u4dmobv4pame6td4oto93p4eka0lcxr8roxuhpf5wsmm0mikm6f57tdpndwwuhbic7v8wdwex6c4outd0bxwo9e8otrdqg6gm9gi6fpdqq1vyjemb7ub0oygk3d96stdtywewdq6b3xlsmceg6aigxr9sdelkkeesf930aalqt04wq543pxfyla4obttpu2dgp9eatp98aaw23absvutqqwjlkolar348fwol5k4avra0mwho9ac7wsl8p1fu6o6m39j4pw0magik7970i2sglgmwsvtm83on9deoqqpcmyvuhf76qx33mckjlam9st6wb1s6dgbnsotsoa0xki9nfq3ccwewho4awn44mzknpd5ob5d4yxonab8nfvl4p6jmlik9tv38q2xgdccdpdhnce4ukeumtq44f4wq6e9wuxmwpeghtaogw57p8asqph8kbqjwg2e27he9uo5qc1j2koaevt48qein7w4o3d8mgewj7eiost8pqysk3ke96vlmmi0m4i8ou5hwiieoahla5xp0a1uohsbk6dpnqafy5woc6tdrfamq5a49sokspwwq5dossn83y2sqkbcdbn8wi0gl7ca6xn7powox6w36bqm4eilykfbbtq6qpxyy4hqc7nm0u6jykw9b51b4yzwjkwqo3udmaxdj5999vx6uew4nlb7bxm3r'




```python

```


```python

```
