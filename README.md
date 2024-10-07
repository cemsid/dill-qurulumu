# Dill-qurulumu


> Qurulum çox da çətin deyil. Sadəcə termius vəya başqa terminallara aşağıdaki kodları bir bir girməyiniz kifayətdir. Hərhansısa sualınızda sizə köməklik edə bilərəm. Telegramdan mənimlə əlaqəyə keçə bilərsiniz: @cemsidesedov

> Yeni bir dil düyünü başlatmaq. Əvvəllər heç dil node işlətməmiş bir hostda yeni node başlatmaq üçün aşağıdakı addımları izləyin.

> Dil Node skriptini yükləyin və işə salın. Terminalınızı açın və yeni bir Dill nodesini başlatmaq üçün aşağıdakı əmri icra edin:

`curl -sO https://raw.githubusercontent.com/DillLabs/launch-dill-node/main/dill.sh && chmod +x dill.sh && ./dill.sh`

![image](https://github.com/user-attachments/assets/7b469a9e-2db3-403f-84a7-fc1bd33f4f76)

> 1 deyib davam edin.

![image](https://github.com/user-attachments/assets/eef989f3-c7a2-49f2-b5fc-ceceaa031106)

> Daha sonra təkrardan 1 deyib davam edin.

![image](https://github.com/user-attachments/assets/23fb172b-e5f9-414a-a5d4-0fdebc68d16d)

> Sizə memoric (validatorun memoricini) verəcək. Bir yerə qeyd edin (mən adətən driverdə yaddaşa verirəm). Sonra enterə basın

![image](https://github.com/user-attachments/assets/e0ba6b06-4cdb-4024-9d71-daaa987450b6)

> Sizə belə bir yazı gələcək yəni memorcilərin hara yazildigini göstərir. 2 dəfə soruşacaq enter deyin. 

![image](https://github.com/user-attachments/assets/e941a502-d6ed-4a67-b76e-60cb01709345)

> Burada hansı validatoru qurmaq istədiyinizi soruşacaq. Qeyd edim ki 3600 ədəd olan light validatordu. 3600 olan isə full validatordu.

> Mən 1 seçib davam edəcəm. 

![image](https://github.com/user-attachments/assets/ebe34e6b-a69d-46ba-a215-7218f2f9b630)

> Bura testnetin sonunda hədiyyə tokenlərin (yəni qazandığınız tokenlərin) hansı kaşloka gələcəyini seçirsiz. (metamask açıb kaçlok alabilərsiz)

![image](https://github.com/user-attachments/assets/722b0812-488f-44bf-beba-dea94125511b)

> Sizdən təkrar evm adresinizi girməyinizi istəyəcək. 2 dəfə eyni kaşlok ünvanını qeyd edib enterə basırsınız.

![image](https://github.com/user-attachments/assets/720f92ae-a966-4f1b-9ec2-8cdf4804c98c)

> Bu ekran gəldisə validatorunuz prooblemsiz qurulub deməkdir. Bir dəfə də enter deyirik. 

![image](https://github.com/user-attachments/assets/39d7b7d3-3e4e-4cb6-9886-8a084558686b)

> Validatoru problemsiz qurduq :)


# Bəs Stake?

> Stake etməsək validatorumuz işləməz və bizə heç bir xeyri olmaz. Gəlin stake etməyi öyrənək.


![image](https://github.com/user-attachments/assets/9a5fdf3e-d801-4c62-a0ae-14c69c2e3aee)

> Dillin rəsmi discord kanalına gəlirik. memoriclərin saxladığınız metamask kaşlokunun adresini discordda alps bölümünə yazacaqsınız.

> Aşağıdakı kimi yazmalısınız:

> $request 0x4673a84eEDe48F520357dC63A8b730c8115D76F9

![image](https://github.com/user-attachments/assets/2ae92166-ce31-42e8-a11c-c9797caf0749)

> Mən qabaqcadan aldığım üçün indi ala bilmirəm. Seçilsəniz sizə test tokenləri göndəriləcək.

> Stake etmək haqqında bir link var: https://dill.xyz/docs/RunANode/Alps#staking


> Qısaca anlatmaq gerekirse bu linkə keçid edirsiz. Daha sonra sunucuya aşağıdaki kodu yazırsız.


> `cd`
> `cd /root/dill/validator_keys`
> `ls`
> 
> Şəkildə gördüyünüz kimi mənim dosyamın adı deposit_data-1728307158.json'dur. Sizdə rəqəm fərqi olacaq böyük ehtimal.

![image](https://github.com/user-attachments/assets/1e157d61-1aa5-456b-9497-cca07e080070)


> Aşağıdakı kod ilə faylın içini görə bilərsiniz (dosyanın rəqəminə diqqət edin).

![image](https://github.com/user-attachments/assets/4497b6b1-9cf0-44a1-90a2-dbe82a5fc054)

"[{" ile başlayan və "}]" ilə bitən (daxil olmaqla) kopya edirik. Şəkildəki kimi:

![image](https://github.com/user-attachments/assets/c94f9203-467b-483d-ad9c-cc152c4473f2)

> Və gəlib aşağıdakı web sayta yapışdırırsız: https://staking.dill.xyz/en/

![image](https://github.com/user-attachments/assets/1cdb9eed-eb86-4303-8b07-03d73a2ecacc)

> Daha sonra Continue butonuna click edirik.

![image](https://github.com/user-attachments/assets/3c7176c2-f288-4a0c-b6eb-34a05a830ab2)


> Məndə token yoxdur deyə stake edə bilmirəm. 2 dəfə stake etmişəm. Bu qədər. Sağolun.




