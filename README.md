# hse22_project
Ссылка на колаб:https://colab.research.google.com/drive/1-XZnVvL7X2_hERvxX8N2cNnm39-LEjPp?usp=sharing
## 1. Таблица аннотированных генов

|Название организма               |Кол-во хромосом|Длина генома|Кол-во генов |Кол-во участков Z-ДНК  |Кол-во предсказанных участков Z-ДНК* |Общая длина участков Z-ДНК*|
|:-------------------------------:|:-------------:|:----------:|:-----------:|:---------------------:|:---------------------:|:-------------------------:|
|Bradyrhizobium cosmicum          |1              |7231841     |6842         |7231841                |118178                 |1138998                    |
|Bradyrhizobium oligotrophicum S58|1              |8264165     |7182         |8264165                |133452                 |1283154                    |
|Bradyrhizobium amphicarpaeae     |1              |7044517     |6551         |7044517                |114802                 |1106630                    |
|Bradyrhizobium betae             |1              |7150095     |6931         |7419402                |121096                 |1165502                    |
|Bradyrhizobium elkanii USDA 61   |1              |9548186     |8870         |9649995                |144519                 |1379100                    |


## 2. Распределение участнов Z-ДНК
Распределение Z-ДНК по промоторам, гену и межгенному пространству:

<img width="436" alt="image" src="https://user-images.githubusercontent.com/93148620/173431937-84d3ca8a-ce69-4eb6-8b9b-a16dab3672f1.png">

## 3. Гистограмма значений zh-score  

<img width="336" alt="image" src="https://user-images.githubusercontent.com/93148620/173432160-a02e99a6-c7e7-4bb6-87c2-8143ab1cf3a9.png">
<img width="326" alt="image" src="https://user-images.githubusercontent.com/93148620/173432326-3abf6849-21d6-4d7e-9e7c-b8a90a5c727b.png">
<img width="328" alt="image" src="https://user-images.githubusercontent.com/93148620/173432376-cb89971b-2291-48fb-87d8-9d589374df01.png">
<img width="325" alt="image" src="https://user-images.githubusercontent.com/93148620/173432413-74f16a7e-5024-4831-8e16-2426a0e5725e.png">
<img width="323" alt="image" src="https://user-images.githubusercontent.com/93148620/173432478-312a0286-89a4-46a7-953b-842a60a37028.png">

## 4. Z-ДНК и гомологичные гены разных организмов
### 4.1 Информация по полученным гомологичным кластерам
Всего кластеров: 7200 
Гистограмма кластеров по кол-ву разных геномов в кластере

<img width="350" alt="image" src="https://user-images.githubusercontent.com/93148620/173435543-2cafdde1-db16-495f-bb54-059fd359bfd1.png">

### 4.2. Таблица с информацией по выбранным кластерам
<table>
    <thead>
        <tr>
            <th>Кластера</th>
            <th>Кол-во генов</th>
            <th>Гены</th>
            <th>Расположение Z-ДНК</th>
            <th>Z-Hunt score</th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td rowspan=5>Cluster 1</td>
            <td rowspan=5>5</td>
            <td rowspan=1>WP_015685937.1</td>
            <td rowspan=1>Промотор</td>
            <td rowspan=1>4546, 981, 3429, 138924, 138924, 13714</td>
        </tr>
        <tr>
            <td rowspan=1>WP_015666726.1</td>
            <td rowspan=1>Промотор</td>
            <td rowspan=1>981, 2997, 981, 884, 2943, 884, 2761</td>
        </tr>
        <tr>
            <td rowspan=1>WP_094890408.1</td>
            <td rowspan=1>Промотор</td>
            <td rowspan=1>884, 138924,28781, 138924, 3429, 884, 981, 981 </td>
        </tr>
        <tr>
            <td rowspan=1>WP_151650075.1</td>
            <td rowspan=1>Промотор</td>
            <td rowspan=1>4546, 1693, 3429, 28781, 8923, 13714</td>
        </tr>
        <tr>
            <td rowspan=1>WP_172648017.1</td>
            <td rowspan=1>Промотор</td>
            <td rowspan=1>38834, 1229, 2264, 884, 13714, 1431, 4546</td>
        </tr>
    </tbody>
    <tbody>
        <tr>
            <td rowspan=5>Cluster 2</td>
            <td rowspan=5>5</td>
            <td rowspan=1>WP_015685457.1</td>
            <td rowspan=1>Промотор</td>
            <td rowspan=1>3429, 884, 981, 13713, 884, 762, 908, 908</td>
        </tr>
        <tr>
            <td rowspan=1>WP_015666189.1</td>
            <td rowspan=1>Промотор</td>
            <td rowspan=1>3429, 2752, 1627, 3429, 884, 884, 884</td>
        </tr>
        <tr>
            <td rowspan=1>WP_094892032.1</td>
            <td rowspan=1>Промотор</td>
            <td rowspan=1>1117, 908, 884, 908, 13714, 884, 981, 884, 884</td>
        </tr>
        <tr>
            <td rowspan=1>WP_151649691.1</td>
            <td rowspan=1>Промотор</td>
            <td rowspan=1>884, 884, 981, 138924, 884, 908, 884, 908</td>
        </tr>
        <tr>
            <td rowspan=1>WP_018272086.1</td>
            <td rowspan=1>Промотор</td>
            <td rowspan=1>3429, 884, 884,884, 908 </td>
        </tr>
    </tbody>
    <tbody>
        <tr>
            <td rowspan=5>Cluster 3</td>
            <td rowspan=5>5</td>
            <td rowspan=1>WP_015685895.1.1</td>
            <td rowspan=1>Промотор</td>
            <td rowspan=1>1738, 3429, 8923, 13714, 13714, 981</td>
        </tr>
        <tr>
            <td rowspan=1>WP_015666663.1</td>
            <td rowspan=1>Промотор</td>
            <td rowspan=1>884, 570, 2963, 884, 13714, 13714, 981</td>
        </tr>
        <tr>
            <td rowspan=1>WP_094890443.1</td>
            <td rowspan=1>Промотор</td>
            <td rowspan=1>13714, 884, 884, 884, 1117, 3429</td>
        </tr>
        <tr>
            <td rowspan=1>WP_151650043.1</td>
            <td rowspan=1>Промотор</td>
            <td rowspan=1>1738, 3429, 884, 8923, 506, 884, 981</td>
        </tr>
        <tr>
            <td rowspan=1>WP_026192730.1</td>
            <td rowspan=1>Промотор</td>
            <td rowspan=1>884, 981, 1356, 865, 13714, 1516, 884, 784</td>
        </tr>
    </tbody>
    <tbody>
        <tr>
            <td rowspan=5>Cluster 4</td>
            <td rowspan=5>5</td>
            <td rowspan=1>WP_015685883.1</td>
            <td rowspan=1>Промотор</td>
            <td rowspan=1>1203, 1091, 981, 981, 3429,784</td>
        </tr>
        <tr>
            <td rowspan=1>WP_015666659.1</td>
            <td rowspan=1>Промотор</td>
            <td rowspan=1>884, 1091, 3429, 579</td>
        </tr>
        <tr>
            <td rowspan=1>WP_094890457.1</td>
            <td rowspan=1>Промотор</td>
            <td rowspan=1>884, 3429, 981, 1091, 740</td>
        </tr>
        <tr>
            <td rowspan=1>WP_151650028.1</td>
            <td rowspan=1>Промотор</td>
            <td rowspan=1>884, 1091, 3429, 3429, </td>
        </tr>
        <tr>
            <td rowspan=1>WP_016842487.1</td>
            <td rowspan=1>Промотор</td>
            <td rowspan=1>3993, 1091, 3429, 784, 4325</td>
        </tr>
    </tbody>
    <tbody>
        <tr>
            <td rowspan=5>Cluster 5</td>
            <td rowspan=5>5</td>
            <td rowspan=1>WP_015688041.1</td>
            <td rowspan=1>Промотор</td>
            <td rowspan=1>884, 981, 1091, 884, 3429</td>
        </tr>
        <tr>
            <td rowspan=1>WP_015668717.1</td>
            <td rowspan=1>Промотор</td>
            <td rowspan=1>570, 908, 981, 810, 1091, 506</td>
        </tr>
        <tr>
            <td rowspan=1>WP_094892725.1</td>
            <td rowspan=1>Промотор</td>
            <td rowspan=1>981, 1091, 1091, 1203, 981, 884, 2173</td>
        </tr>
        <tr>
            <td rowspan=1>WP_151643413.1</td>
            <td rowspan=1>Промотор</td>
            <td rowspan=1>884, 981, 1203, 1091, 884, 3429</td>
        </tr>
        <tr>
            <td rowspan=1>WP_172647090.1</td>
            <td rowspan=1>Промотор</td>
            <td rowspan=1>138924, 884, 1091, 981, 908, 884</td>
        </tr>
    </tbody>
    <tbody>
        <tr>
            <td rowspan=5>Cluster 6</td>
            <td rowspan=5>5</td>
            <td rowspan=1>WP_041748545.1</td>
            <td rowspan=1>Промотор</td>
            <td rowspan=1>3429, 2091 </td>
        </tr>
        <tr>
            <td rowspan=1>WP_015669248.1</td>
            <td rowspan=1>Промотор</td>
            <td rowspan=1>803, 884, 13714, 884, 3429</td>
        </tr>
        <tr>
            <td rowspan=1>WP_094895021.1</td>
            <td rowspan=1>Промотор</td>
            <td rowspan=1>3429</td>
        </tr>
        <tr>
            <td rowspan=1>WP_151644160.1</td>
            <td rowspan=1>Промотор</td>
            <td rowspan=1>3429, 8323</td>
        </tr>
        <tr>
            <td rowspan=1>WP_172648516.1</td>
            <td rowspan=1>Промотор</td>
            <td rowspan=1>884, 3429, 961, 28781, 8323, 753, 3429</td>
        </tr>
    </tbody>
</table>


### 4.3. Множественное белковое выравнивание для каждого выбранного кластера

<details>
  <summary>Cluster №1</summary>
  
  ```
  >WP_151650075.1_Bradyrhizobium_betae
MRSIKQPGLPVTERIQWVEARGRAFSFTLQAGLPLLEAARRGFAAEGFAGGVLNFGSGTLAPFAYVMPALSKTGENAAFY
SDTYRPGGVTRTRLGSMTLGTRDGAPFFHCHGLWLEADGKASGGHMLPDETVVAEAFEVAAFGLDGAIFTAEPDPETSFK
LFGPVAVASTGARATNRAFALRLRPNQDFAGCLEEFCRAHGIAHAKIHGGVGSTIGARFIHGGVTEPFATELAITAGAIE
PGDSGALEAALDVALIDYTGGIAEGRLIRGDNPVLMTMELVLEVLG-----
>WP_094890408.1_Bradyrhizobium_amphicarpaeae
MRSIKQPGAAIAERIQWVEARGRAFGFTLQAGLPLLEAARRGFAAEGFSGGVVNFRHGALGPFAYVMPALSKTGENAAFY
SDTYRPGGVTRTKLGSMTLGTRDGAPFFHCHGLWTEAGGKASGGHMLPDETVVAEPFEVEAFGLDGAMFTAEPDPETNFK
LFGPVAAARTGARATSRAFALRLRPNQDFAGCLEDFCRAHGVARAKIHGGVGSTIGARFTHGGVTEPFATELAVTAGLIA
PGPSGALEAALDVALVDYTGGLAEGRLVRGDNPVLMTMELVLEALD-----
>WP_015685937.1_Bradyrhizobium_cosmicum
MRSIKQPGSPATERIQWVEARGRAFSFTLQAGLPLLEAARRGFAAEGFAGGVLNFGRGTLGPFAYVMPALSKTGENAAFY
SDIYRPGGVTRTRLGSMTLGTRDGAPFFHCHGLWLEADGTASGGHMLPDETVVAEAFEVAAFGVDGAIFTAEPDPETNFK
LFGPVAAASTGARATSRAFALRLRPNQDFAGCLEEFCRARGIAHAKIHGGVGSTIGARFTHGGVTEPFATELAITAGTIA
PGAAGALEAALDVALIDYTGGIAEGRLIRGDNPVLMTMELVLEVLG-----
>WP_015666726.1_Bradyrhizobium_oligotrophicum_S58
MRSIKQPGTPIAERIQWVEARGRAFTFMLEQGLPLLEAARRGFAAQGFAGGVLDIRGGALGPFAYVMPALSKTPDHAAFY
SDTYRPPGITRLSTATMTLGVRDGAPFFHCHALWTEEGGRAGGGHILPEETIVAEPFEVAAFGLDGAIFTAEPDVETGFK
LFGPVVAAKSGATTDRRAFALRLRPNQDFAGCLEAFCRSLDISSARIRGGVGSTIGARFEDGIVVEPFATELTITSGAIA
PGADG-LEAVLDVALVDYTGALAQGRLVRGDNPVLMTMELVLEVVA-----
>WP_172648017.1_Bradyrhizobium_elkanii_USDA_61
MRSIAQPGAPHPERIQWVSARGRAFSFVLEAGIPLLEAVRRGFAAEGFSGGVLSARGGAVGPFAYVMPALSKDGVNAAFY
SDTFRPDGVTRLKLAALTFGERDGAPFFHCHGLWTEADGRFNGGHMLPDETIVAEPFEVNAFGIDGATFLAKADSETNFK
LFGPVASAPRGAKTTSHAFALRLRPNQDFACALEGFCRQHGILRARLHGGVGSTIGAVFTDGHSVVPFATELAVTAGEIA
PDADGRLHAELDIALVDYLGGIAEGRLVRGDNPVLMTMELALEVLAEAEQP

  ```
</details>

<details>
  <summary>Cluster №2</summary>
  
  ```
  >WP_151649691.1_Bradyrhizobium_betae
MPETSASRPASTILLLRDGA-------KEIEVFMMVRHHQIEFNSGALVFPGGSVDAGDQEIVARSDLYSGGEGLSEADR
GFRIAAIRETFEESGILLARAQDSGTPIDARRAGEIADAHRVALNEHKISFLSILADNGLQLALDTLLPYAHWITPEGLP
KRFDTWFFLAAAPPDQLGAHDGRESTDSIWVSPREAVEGGESGRFKLPFPTTRNLIRLAKQGSVDAALDHARGLSIVTVM
PVMTKTE-AGRQLRIPREAGYDGEVFDVGAVG
>WP_094892032.1_Bradyrhizobium_amphicarpaeae
MAETSASRPASTILLLRDGEKADGKGRGEIEVFMMVRHHQIEFNSGALVFPGGSVDAGDNEIVARSDLYSGGEGLSEADR
GFRIAAIRETFEESGILLARAKGTGTPVDARRAGELADAHRIALNEHKISFLKILDDNGLQLALDTLVPYAHWITPEGMP
KRFDTWFFLAAAPPDQLGAHDGRESTDSIWVSPREAVEGGESGRFKLPFPTTRNLIRLAKQASVGAALDHARGMSIVTVM
PVMTKTE-TGRQLRIPREAGYDGEVFEVGALG
>WP_015685457.1_Bradyrhizobium_cosmicum
MPETSASRPASTILLLRDGA-------KDIEVFMMVRHHQIEFNSGALVFPGGSVDAGDQEIVARADLYSGGEGLSEADR
GFRIAAIRETFEESGILLARAKDSGTPIDARRAGEIADAHRVALNEHKISFLSILADNGLQLALDTLVPYAHWITPEGLP
KRFDTWFFLAAAPPDQLGAHDGRESTDSIWVSPREAVEGGESGRFKLPFPTTRNLIRLAKQGSVDAALDHARGLSIVTVM
PVMTKTE-TGRQLRIPREAGYDGEVFEVGAVG
>WP_015666189.1_Bradyrhizobium_oligotrophicum_S58
MADAAAVRPASTVLLLRDSATA-----REIEVFMMVRHHQIEFNSGALVFPGGSVDKGDQEIAGKPELYAGDEGLAAEAL
GFRIAGVRETFEESGILLARPRRSETLIDAAAAREIEAAHRLALCEGKVSFLEVLEAHGLVLALDTLVAYAHWITPEGMP
KRFDTWFFLAAAPPDQLGAHDGRESTDSVWVSPREALAGGEDGRFKLPFPTTRNLIRLGKQPAVADALAGARGMDIVTVM
PVMTKTADGGRQLRIPREAGYDGEVFEFGAAG
>WP_018272086.1_Bradyrhizobium_elkanii_USDA_61
MNEIVAPRLASTVLLLRDGTSS-----REIEVFMMVRHHQIEFNSGALVFPGGSVDKNDKEIAADPALYSGGEGLDGDAL
GFRIAAIRETFEESGILLARPQGSKHLVDAKRANEIATAHRAALNEGKIGFLKVLTDNGMVLALDELVPYAHWITPEGMP
KRFDTWFFLAAAPPEQLGAHDGKESTDSIWVSTREALEGGETGRFKLPFPTTRNLIRLGKQPNVGAALADSKGKPIVAVM
PVMTKTA-TGRQLRIPKEAGYDGEVFDVGALG
  ```
</details>

<details>
  <summary>Cluster №3</summary>
  
  ```
  >WP_094890443.1_Bradyrhizobium_amphicarpaeae
MRTSRRAIVAFVLGASAL--AAPALAFDGAPVNPKDATIPVVTALPNATGGVRGK-V--APAAV---PQETSLSALQYAA
EGGHPIAQWKLGRMYANGDGVAQDDLRAFEYFSRIANAHAEDSPSAPQAQIVANAFVALGRYYLSGIPNSKIKSDPDRAR
EMFSYAASYFGNADAQYDLARLYLKTPDASREDFRYGARWLGLAAQKGQHQAQALLGQMLFNGDRLPRQAARGLMWLTLA
RDSAGTEETWIKENYNRAFAKASDDDRAMCLQMLEQWVQGRRE
>WP_015666663.1_Bradyrhizobium_oligotrophicum_S58
MRTSDRIIFALMLGVAPLTWAAPSFAFDGAPVNQ-EPAIPVAGAQSG-AGALRKA-V---PATTSSTSPTQSLTALQYAA
EEGHPVAQWKLGRMYAAGDGVVRDDIRAFDYFSRIANAHAEDSPSAPQAQIVANAFVALGRYYLSGIPNSKVKADPDRAR
EMFSYAASYFGNADAQYDLARIYLKTADASRDDFRYGARWLGLAAQKGQHQAQALLGQMLFNGDRLPRQAARGLMWLTLA
RDSAGPDEAWIKESYNRAFAKASDDDRASALQMLESWVQGKRE
>WP_026192730.1_Bradyrhizobium_elkanii_USDA_61
MRTFRRTILAFALGAIPV--AGPGFGFDGAPVNPQDTVLPVVSPQPGTAGALKRAATPVAPAAT---SPTSSFSTLQYQA
EGGHPVAQWKLGKMYAEGDGVIQDDMRAFEYFSRIANAHAEDSPSAPQASIVANAFVALGRYYLSGIPNSKVKADTERAR
EMFSYAASYFGNADAQYDLARLYLKTPDASRDDFRYGARWLGLAAQKGQHQAQALLGQMLFNGDRLPPQRARGLMWLTLA
RDSATPDEAWIKESYNRAIAKASEDDRAMALQMLEHWVQGRRD
>WP_015685895.1_Bradyrhizobium_cosmicum
MRTSRRAIVAFVLGASAL--AAPAFAFDGSPANNKDATIPVVTTLPGTAGTVRSK-V---PAPT----QETSLSALQYAA
EGGHPIAQWKLGRMYANGDGVVQDDVRAFEYFSRIANAHAEDSPSAPQAQIVANAFVALGRYYLSGIPNSKIKPDQDRAR
EMFSYAASYFGNADAQYDLARLYLKTPDASREDFRYGARWLGLAAQKGQHEAQALLGQMLFNGDRLPRQAARGLMWLTLA
RDSAGAEETWIKENYNRAFAKASDDDRAMCLQMLEQWVQGRRD
>WP_151650043.1_Bradyrhizobium_betae
MRTSRRAIVAFVLGASAL--AAPAFAFDGSPANNKDATIPVVTTLPGTAGTVRSK-V---PAAT----QETSLSALQYAA
EGGHPIAQWRLGRMYANGDGVAQDDVRAFEYFSRIANAHAEDSPSAPQAQIVANAFVALGRYYLSGIPNSKIKPDQDRAR
EMFSYAASYFGNADAQYDLARLYLNTPDASREDFRYGARWLGLAAQKGQHEAQALLGQMLFNGDRLPRQAARGLMWLTLA
RDSAGAEETWIKENYNRAFAKASDDDRAMCLQMLEQWVQGRRE
  ```
</details>

<details>
  <summary>Cluster №4</summary>
  
  ```
  >WP_015685883.1_Bradyrhizobium_cosmicum
MADTSFDVIIIGSGPGGYVAAIRAAQLGLKTAIVEKSYLGGICLNWGCIPTKALLRSAEIYHYMQHAKDYGLSADNISFD
PKAVVQRSRGVSKRLNDGVGFLMKKNKVSVIWGAASIDAPGKVTVKKSDAEAPKGALGEGSYQAKHIIVATGARPRVLPG
LEPDKKLIWTYFEAMVPEKMPKSLLVVGSGAIGIEFASFFRTMGSDVTVVEVLPQILPVEDAEIAGLARKRLEKQGIKIM
SSTKVTKLEKKADSVVATIDDGKGKPVTTEFERVISAVGVVGNIENLGLEKLGVKTDRGCIVIDGYGKTNVPGIYAIGDV
AGPPMLAHKAEHEGVVCVEAIKGLHPHPMDKLLIPGCTYCNPQVASVGLTEAKAKEGGREIRVGRFPFVGNGKAIALGED
QGLVKVIFDKKTGQLLGAHMVGAEVTELIQGYVVAMNLETTEEELMHTVFPHPTLSEMMKEAVLDAYGRVLNI
>WP_016842487.1_Bradyrhizobium_elkanii_USDA_61
MADTSFDVIIIGSGPGGYVTAIRAAQLGFKTAIVEKSYLGGICLNWGCIPTKALLRSAEIYHYMQHAKDYGLSADNVSFD
PKAVVQRSRGVSKRLNDGVGFLMKKNKVTVIWGEATIDAPGKITVKKSAVEAPKGASGEGTYQAKHIIVATGARPRVLPG
LEPDKKLVWTYFEAMVPERMPKSLLVVGSGAIGIEFASFFHTMGADVTVVEVLPQILPVEDAEIAGLARKRFEKMGIKIL
TSTKVTKLEKKADSVVATIDDGKGQPQTKEFERVISAVGVVGNIENLGLEKLGVKTDRGCIVIDGLGKTNVPGIYAIGDV
AGPPMLAHKAEHEGVICIEAIKGLHPHPMDKLMIPGCTYCNPQVASVGLTEAMAKEGGREIRVGRFPFVGNGKAIALGED
QGLVKVVFDKKTGQLLGAHMIGAEVTELIQGYVVAMNLETTEEELMHTVFPHPTLSEMMKEAVLDAYGRVLNI
>WP_094890457.1_Bradyrhizobium_amphicarpaeae
MADTSFDVIIIGSGPGGYVAAIRAAQLGLKTAIIEKSYLGGICLNWGCIPTKALLRSAEIYHYMRHAKDYGLSADNISFD
PKAVVQRSRGVSKRLNDGVGFLMKKNKVSVIWGAASIDAPGKITVKKSDVEAPKGALGEGSYQAKHIIVATGARPRVLPG
LEPDKKLIWTYFEAMVPEKMPKSLLVVGSGAIGIEFASFFHTMGSDVTVVEVLPQILPVEDAEIAGLARKRLEKQGIKIM
SSTKVTKLEKKADSVVATIDDGKGKPVTTEFERVISAVGVVGNIENLGLEKLGVKTDRGCIVIDGYGKTNIPGIYAIGDV
AGPPMLAHKAEHEGVICVEAIKGLHPHPMDKLLIPGCTYCNPQVASVGLTEAKAKEGGREIRVGRFPFVGNGKAIALGED
QGLVKVIFDKKTGQLLGAHMVGAEVTELIQGYVVAMNLETTEEELMHTVFPHPTLSEMMKEAVLDAYGRVLNI
>WP_015666659.1_Bradyrhizobium_oligotrophicum_S58
MADTSFDVIIIGSGPGGYVTAIRAAQLGFKTAIIEKSYLGGICLNWGCIPTKALLRSAEIYHYMQHAKDYGLSAEKISYD
PKAVVQRSRGVSKRLNDGVGFLMKKNKVQVIWGKAAIDAPGKITVTKSDVEAPKGTLGEGVYQAKHIIVATGARPRVLPG
LEPDKKLVWTYFEAMVPDKMPKSLLVVGSGAIGIEFASFFRTMGSEVTVVEVLPQILPVEDAEIAGIARKQLEKQGLKIM
TGAKVTKLDKKSDSVVATIDDGKGKTEAVEFERVISAVGVVGNIENLGLEKLGVKTDRGCVVIDGYGKTNVPGIYAIGDV
AGPPMLAHKAEHEGVVCIEAIKGLHPHAMDKNLIPGCTYCHPQVASVGLTEAKAKEQGRDIRVGRFPFVGNGKAIALGED
QGLVKVIFDKKTGQLIGAHMVGAEVTELIQGYVVAMNLETTEEELMHTVFPHPTLSEMMKEAVLDAYGRVLNM
>WP_151650028.1_Bradyrhizobium_betae
MADTSFDVIIIGSGPGGYVAAIRAAQLGLKTAIVEKSYLGGICLNWGCIPTKALLRSAEIYHYMQHAKDYGLSADNISFD
PKAVVQRSRGVSKRLNDGVGFLMKKNKVSVIWGAASIDAPGKVTVKKSDAEAPKGVLGEGSYQAKHIIVATGARPRVLPG
LEPDKKLIWTYFEAMVPEKMPKSLLVVGSGAIGIEFASFFRTMGSDVTVVEVLPQILPVEDAEIAGLARKRLEKQGIKIM
SSTKVTKLEKKADSVVATIDDGKGKPVTTEFERVISAVGVVGNIENLGLEKLGVKTDRGCIVIDGYGKTNIPGIYAIGDV
AGPPMLAHKAEHEGVICVEAIKGLHPHAMDKLLIPGCTYCNPQVASVGLTEAKAKEGGREIRVGRFPFVGNGKAIALGED
QGLVKVIFDKKTGQLLGAHMVGAEVTELIQGYVVAMNLETTEEELMHTIFPHPTLSEMMKEAVLDAYGRVLNI
  ```
</details>

<details>
  <summary>Cluster №5</summary>
  
  ```
  >WP_151643413.1_Bradyrhizobium_betae
MTGLTHRQAEILNIARASGRVMVEELARKFEVSAQTIRKDLNDLCERRSLTRIHGGAIIASGVENLAYEARRFVAADEKK
AIGVAAASLIPNGCSLFINIGTTTEEVASALTSHEDLLVITNNLNVAMLLYRHPRIEVVVAGGTVRRADGAVVGSTATQL
IGQFKVDYAIIGASAIDEEGALLDFDYREVQVAQAIIANARSVMLVADSTKLRRSAPVRIAHISQIQTFVTDQELPERLA
TICHSKGIEVMAAMPKGAGESDEAAAEPPQDPGSVVRLR
>WP_172647090.1_Bradyrhizobium_elkanii_USDA_61
MAGLSHRQTEILNIARAFGRVMVEDLAKRFEVSAQTIRKDLNDLCDQRSLTRIHGGAIIASGVENLAYEARRFVAAEEKK
AIGAAAAARIPNGCSLFINIGTTTEEVASALTSHEDLLVITNNLNVAMLLYRHPRIEVVVAGGTVRRADGAVVGSTATQL
IGQFKVDYAIIGASAIDEEGALLDFDYREVQVAQAIIANARNVMLVSDSTKLRRSAPVRIAHMSQIQTFVTDSPLPAGLA
SICHSRGIEVVVAMDKPQVDLDDNG---PDAAPATLRSA
>WP_015668717.1_Bradyrhizobium_oligotrophicum_S58
MAVLSQRQTDILNIARASGRVMVEDLSRRFEVSAQTIRKDLNDLCEQRALTRIHGGAIIASGVENLAYEARRFVAADEKK
AIGAAAAARIPNGSSLFINIGTTTEEVASALSSHQDLLVITNNLNVAMLLYPHPRIEVIVAGGTVRRSDGGVVGSTATQL
IGQFKVDYAIIGASAIDEEGALLDFDYREVQVAQAIIANARSVMLVADSTKLHRSAPVRIAHLSQIQTFVTDRPLPDGLA
SLCHSRGIEVISAMPAD--DTDEAADATETTSSTVLRRA
>WP_015688041.1_Bradyrhizobium_cosmicum
MTGLTHRQAEILNIARASGRVMVEELARKFEVSAQTIRKDLNDLCERRSLTRIHGGAIIASGVENLAYEARRFVAADEKK
AIGIAAASLIPNGCSLFINIGTTTEEVASALTSHEDLLVITNNLNVAMLLYRHPRIEVVVAGGTVRRADGAVVGSTATQL
IGQFKVDYAIIGASAIDEEGALLDFDYREVQVAQAIIANARSVMLVADSTKLRRSAPVRIAHISQIQTFVTDQELPERLA
TICHGKGIEVMAAMPKGA-DVDDAAE-PPQEAAPVVRLR
>WP_094892725.1_Bradyrhizobium_amphicarpaeae
MTGLTHRQAEILNIARASGRVMVEELARRFEVSAQTIRKDLNDLCERRSLTRIHGGAIIASGVENLAYEARRFVAADEKK
AIGAAAASLIPNGCSLFINIGTTTEEVASALTSHEDLLVITNNLNVAMLLYRHPRIEVVVAGGTVRRADGAVVGSTATQL
IGQFKVDYAIIGASAIDEEGALLDFDYREVQVAQAIIANARSVMLVADSTKLRRSAPVRIAHMTQIQTFVTDQELPERLA
TICHSKGIEVMAAMPKGAGDVDDVQA-EVQEASPVVRLR
  ```
</details>

<details>
  <summary>Cluster №6</summary>
  
  ```
  >WP_094895021.1_Bradyrhizobium_amphicarpaeae
-MRDASFILG---RA-GSRVLAIVLLTAATALGGCAG-GGGAANSYAMAPSTGSGATVAFESIDGPPPQVFDRMVGVLDS
ESKLRSLSVVSREGSAAYRVRSYLSAQVVRGKTVIAWVWDVYDANQQRALRLSGEEPTAAKGGRDPWNAADDLVLRKIAQ
AGFSGLSNMISGTP---DAPGTAPGLRGPAVASV-APIGPTP-EMPASALGYAER
>WP_015669248.1_Bradyrhizobium_oligotrophicum_S58
MMRGAPTPLRLISRAAQHACVAAVLITSAATLGGCASSSGGPANAYAMAPAS-DSATIAFEQIDGPPPQIFDRMVSVLDS
ESKLRSLAIVSREAPAAYRVRTYLSAQVVSGKSVISWVFDVYDRNQQRALRLSGEEPI-GRGGRDPWNAVDDMVLRKIAQ
AGFSGLSGMLNGTAPAGSAPAAAPATRGPAVAAT-EPASPSAGGTSVAALGYTDH
>WP_172648516.1_Bradyrhizobium_elkanii_USDA_61
-MREASNRQFQTGTA-ARAAIAGTWLAIACALGGCAA-GGNVADSYAMATPASSGATVAFESIDGPPPQVFDRMVGVLDS
ESKLRSLSIVSRQGAAAYRVRSYLSAQVVRGRTMISWVWDFYDSNQQRALRLSGEEPA-GKAGRDAWAAADDLVLRKIAQ
AGFSGLSSMLNGGP----ADSPAPDLRGPTVASAPAPAAP---E--TVALGYSAD
>WP_041748545.1_Bradyrhizobium_cosmicum
-MRDASSILR---RA-GSRVLAVMLLAAATALAGCAG-GGGAANSYAMAPSAGSGATVAFESIDGPPPQVFDRMVGVLDS
ESKLRSLSVVSREGTAAYRVRSYLSAQVVRGKTVIAWVWDVYDANQQRALRVSGEEPTSAKGGRDPWSAADDLVLRKIAQ
AGFSGLSNMITGTP---DTPSAVPGLRGPAVASV-TPDGP---GLPASALGYAER
>WP_151644160.1_Bradyrhizobium_betae
-MRDASSILR---RA-GSRVLAVMLLAAATALGGCAG-GGSAANSYAMAPSAGSGATVAFESIDGPPPQVFDRMVGVLDS
ESKLRSLSVVSREGTAAYRVRSYLSAQVVRGKTVIAWVWDVYDANQQRALRVSGEEPTSAKGGRDPWSAADDLVLRKIAQ
AGFSGLSNMINGTP---DTPNAVPGLRGPAVASV-TPDGP---EMPAAALGYAER

  ```
</details>


## 4.4. Визуализация расположения участков Z-DNA для каждого выбранного кластера
Я выбрала 6 кластеров. 

![кластер1](https://user-images.githubusercontent.com/93148620/173436827-2df79850-3be7-4a58-bb7e-0fd65bd8a0c9.png)
![Кластер2](https://user-images.githubusercontent.com/93148620/173436866-fcf5d03d-4233-4015-8110-a8290cd9a232.png)
![Кластер3](https://user-images.githubusercontent.com/93148620/173436915-29d280b4-5268-4347-a530-6918c6753072.png)
![Кластер4](https://user-images.githubusercontent.com/93148620/173436949-9c1599a1-3281-4ae1-ae65-570905a5f244.png)
![Кластер5](https://user-images.githubusercontent.com/93148620/173436993-d7a47422-cb46-4c17-ad7e-2c9e4fd3a6c7.png)
![Кластер6](https://user-images.githubusercontent.com/93148620/173437043-76ac6b65-b480-4197-b7c7-44164293f45b.png)
