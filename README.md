# proyek-akhir
ini tugas akhir tentang sampah
## Inilah ide untuk proyek saya:
> aku bakal bikin game tentang sampah, iklim, dan lingkungan
## Inilah jenis proyek saya:
> game web

## Pustaka yang akan saya gunakan: - Pustaka 1 - Pustaka N

## Referensi yang berguna: - Referensi 1 - Referensi N

## Artikel panduan yang akan membantu saya selama pengembangan Sebuah komentar singkat yang akan membantu Anda mengingat tentang apa artikel tersebut... [kata yang dapat diklik yang akan berisi tautan] (https://link_to_the_article)
[Uploading index.html…]()<!DOCTYPE html>
<html lang="en">
from flask import Flask, render_template

app = Flask(__name__)

@app.route("/")
def pertanyaan():
    return render_template("index_html")

@app.route("/")
def jawab(jawaban):
    if jawaban ==
    return render_template("index_html")


[[source]]
url = "https://pypi.org/simple"
verify_ssl = true
name = "pypi"

[packages]
flask = "*"
flask-sqlalchemy = "*"

[dev-packages]

[requires]
python_version = "3.11"

{
    "_meta": {
        "hash": {
            "sha256": "9d49db13e43fbee99e5ce07dca419df8b4a537f0dfd5abff94770cde65b2c82e"
        },
        "pipfile-spec": 6,
        "requires": {
            "python_version": "3.11"
        },
        "sources": [
            {
                "name": "pypi",
                "url": "https://pypi.org/simple",
                "verify_ssl": true
            }
        ]
    },
    "default": {
        "blinker": {
            "hashes": [
                "sha256:c3f865d4d54db7abc53758a01601cf343fe55b84c1de4e3fa910e420b438d5b9",
                "sha256:e6820ff6fa4e4d1d8e2747c2283749c3f547e4fee112b98555cdcdae32996182"
            ],
            "markers": "python_version >= '3.8'",
            "version": "==1.7.0"
        },
        "click": {
            "hashes": [
                "sha256:ae74fb96c20a0277a1d615f1e4d73c8414f5a98db8b799a7931d1582f3390c28",
                "sha256:ca9853ad459e787e2192211578cc907e7594e294c7ccc834310722b41b9ca6de"
            ],
            "markers": "python_version >= '3.7'",
            "version": "==8.1.7"
        },
        "colorama": {
            "hashes": [
                "sha256:08695f5cb7ed6e0531a20572697297273c47b8cae5a63ffc6d6ed5c201be6e44",
                "sha256:4f1d9991f5acc0ca119f9d443620b77f9d6b33703e51011c16baf57afb285fc6"
            ],
            "markers": "platform_system == 'Windows'",
            "version": "==0.4.6"
        },
        "flask": {
            "hashes": [
                "sha256:21128f47e4e3b9d597a3e8521a329bf56909b690fcc3fa3e477725aa81367638",
                "sha256:cfadcdb638b609361d29ec22360d6070a77d7463dcb3ab08d2c2f2f168845f58"
            ],
            "index": "pypi",
            "markers": "python_version >= '3.8'",
            "version": "==3.0.0"
        },
        "flask-sqlalchemy": {
            "hashes": [
                "sha256:4ba4be7f419dc72f4efd8802d69974803c37259dd42f3913b0dcf75c9447e0a0",
                "sha256:e4b68bb881802dda1a7d878b2fc84c06d1ee57fb40b874d3dc97dabfa36b8312"
            ],
            "index": "pypi",
            "markers": "python_version >= '3.8'",
            "version": "==3.1.1"
        },
        "greenlet": {
            "hashes": [
                "sha256:01bc7ea167cf943b4c802068e178bbf70ae2e8c080467070d01bfa02f337ee67",
                "sha256:0448abc479fab28b00cb472d278828b3ccca164531daab4e970a0458786055d6",
                "sha256:086152f8fbc5955df88382e8a75984e2bb1c892ad2e3c80a2508954e52295257",
                "sha256:098d86f528c855ead3479afe84b49242e174ed262456c342d70fc7f972bc13c4",
                "sha256:149e94a2dd82d19838fe4b2259f1b6b9957d5ba1b25640d2380bea9c5df37676",
                "sha256:1551a8195c0d4a68fac7a4325efac0d541b48def35feb49d803674ac32582f61",
                "sha256:15d79dd26056573940fcb8c7413d84118086f2ec1a8acdfa854631084393efcc",
                "sha256:1996cb9306c8595335bb157d133daf5cf9f693ef413e7673cb07e3e5871379ca",
                "sha256:1a7191e42732df52cb5f39d3527217e7ab73cae2cb3694d241e18f53d84ea9a7",
                "sha256:1ea188d4f49089fc6fb283845ab18a2518d279c7cd9da1065d7a84e991748728",
                "sha256:1f672519db1796ca0d8753f9e78ec02355e862d0998193038c7073045899f305",
                "sha256:2516a9957eed41dd8f1ec0c604f1cdc86758b587d964668b5b196a9db5bfcde6",
                "sha256:2797aa5aedac23af156bbb5a6aa2cd3427ada2972c828244eb7d1b9255846379",
                "sha256:2dd6e660effd852586b6a8478a1d244b8dc90ab5b1321751d2ea15deb49ed414",
                "sha256:3ddc0f794e6ad661e321caa8d2f0a55ce01213c74722587256fb6566049a8b04",
                "sha256:3ed7fb269f15dc662787f4119ec300ad0702fa1b19d2135a37c2c4de6fadfd4a",
                "sha256:419b386f84949bf0e7c73e6032e3457b82a787c1ab4a0e43732898a761cc9dbf",
                "sha256:43374442353259554ce33599da8b692d5aa96f8976d567d4badf263371fbe491",
                "sha256:52f59dd9c96ad2fc0d5724107444f76eb20aaccb675bf825df6435acb7703559",
                "sha256:57e8974f23e47dac22b83436bdcf23080ade568ce77df33159e019d161ce1d1e",
                "sha256:5b51e85cb5ceda94e79d019ed36b35386e8c37d22f07d6a751cb659b180d5274",
                "sha256:649dde7de1a5eceb258f9cb00bdf50e978c9db1b996964cd80703614c86495eb",
                "sha256:64d7675ad83578e3fc149b617a444fab8efdafc9385471f868eb5ff83e446b8b",
                "sha256:68834da854554926fbedd38c76e60c4a2e3198c6fbed520b106a8986445caaf9",
                "sha256:6b66c9c1e7ccabad3a7d037b2bcb740122a7b17a53734b7d72a344ce39882a1b",
                "sha256:70fb482fdf2c707765ab5f0b6655e9cfcf3780d8d87355a063547b41177599be",
                "sha256:7170375bcc99f1a2fbd9c306f5be8764eaf3ac6b5cb968862cad4c7057756506",
                "sha256:73a411ef564e0e097dbe7e866bb2dda0f027e072b04da387282b02c308807405",
                "sha256:77457465d89b8263bca14759d7c1684df840b6811b2499838cc5b040a8b5b113",
                "sha256:7f362975f2d179f9e26928c5b517524e89dd48530a0202570d55ad6ca5d8a56f",
                "sha256:81bb9c6d52e8321f09c3d165b2a78c680506d9af285bfccbad9fb7ad5a5da3e5",
                "sha256:881b7db1ebff4ba09aaaeae6aa491daeb226c8150fc20e836ad00041bcb11230",
                "sha256:894393ce10ceac937e56ec00bb71c4c2f8209ad516e96033e4b3b1de270e200d",
                "sha256:99bf650dc5d69546e076f413a87481ee1d2d09aaaaaca058c9251b6d8c14783f",
                "sha256:9da2bd29ed9e4f15955dd1595ad7bc9320308a3b766ef7f837e23ad4b4aac31a",
                "sha256:afaff6cf5200befd5cec055b07d1c0a5a06c040fe5ad148abcd11ba6ab9b114e",
                "sha256:b1b5667cced97081bf57b8fa1d6bfca67814b0afd38208d52538316e9422fc61",
                "sha256:b37eef18ea55f2ffd8f00ff8fe7c8d3818abd3e25fb73fae2ca3b672e333a7a6",
                "sha256:b542be2440edc2d48547b5923c408cbe0fc94afb9f18741faa6ae970dbcb9b6d",
                "sha256:b7dcbe92cc99f08c8dd11f930de4d99ef756c3591a5377d1d9cd7dd5e896da71",
                "sha256:b7f009caad047246ed379e1c4dbcb8b020f0a390667ea74d2387be2998f58a22",
                "sha256:bba5387a6975598857d86de9eac14210a49d554a77eb8261cc68b7d082f78ce2",
                "sha256:c5e1536de2aad7bf62e27baf79225d0d64360d4168cf2e6becb91baf1ed074f3",
                "sha256:c5ee858cfe08f34712f548c3c363e807e7186f03ad7a5039ebadb29e8c6be067",
                "sha256:c9db1c18f0eaad2f804728c67d6c610778456e3e1cc4ab4bbd5eeb8e6053c6fc",
                "sha256:d353cadd6083fdb056bb46ed07e4340b0869c305c8ca54ef9da3421acbdf6881",
                "sha256:d46677c85c5ba00a9cb6f7a00b2bfa6f812192d2c9f7d9c4f6a55b60216712f3",
                "sha256:d4d1ac74f5c0c0524e4a24335350edad7e5f03b9532da7ea4d3c54d527784f2e",
                "sha256:d73a9fe764d77f87f8ec26a0c85144d6a951a6c438dfe50487df5595c6373eac",
                "sha256:da70d4d51c8b306bb7a031d5cff6cc25ad253affe89b70352af5f1cb68e74b53",
                "sha256:daf3cb43b7cf2ba96d614252ce1684c1bccee6b2183a01328c98d36fcd7d5cb0",
                "sha256:dca1e2f3ca00b84a396bc1bce13dd21f680f035314d2379c4160c98153b2059b",
                "sha256:dd4f49ae60e10adbc94b45c0b5e6a179acc1736cf7a90160b404076ee283cf83",
                "sha256:e1f145462f1fa6e4a4ae3c0f782e580ce44d57c8f2c7aae1b6fa88c0b2efdb41",
                "sha256:e3391d1e16e2a5a1507d83e4a8b100f4ee626e8eca43cf2cadb543de69827c4c",
                "sha256:fcd2469d6a2cf298f198f0487e0a5b1a47a42ca0fa4dfd1b6862c999f018ebbf",
                "sha256:fd096eb7ffef17c456cfa587523c5f92321ae02427ff955bebe9e3c63bc9f0da",
                "sha256:fe754d231288e1e64323cfad462fcee8f0288654c10bdf4f603a39ed923bef33"
            ],
            "markers": "platform_machine == 'aarch64' or (platform_machine == 'ppc64le' or (platform_machine == 'x86_64' or (platform_machine == 'amd64' or (platform_machine == 'AMD64' or (platform_machine == 'win32' or platform_machine == 'WIN32')))))",
            "version": "==3.0.3"
        },
        "itsdangerous": {
            "hashes": [
                "sha256:2c2349112351b88699d8d4b6b075022c0808887cb7ad10069318a8b0bc88db44",
                "sha256:5dbbc68b317e5e42f327f9021763545dc3fc3bfe22e6deb96aaf1fc38874156a"
            ],
            "markers": "python_version >= '3.7'",
            "version": "==2.1.2"
        },
        "jinja2": {
            "hashes": [
                "sha256:7d6d50dd97d52cbc355597bd845fabfbac3f551e1f99619e39a35ce8c370b5fa",
                "sha256:ac8bd6544d4bb2c9792bf3a159e80bba8fda7f07e81bc3aed565432d5925ba90"
            ],
            "markers": "python_version >= '3.7'",
            "version": "==3.1.3"
        },
        "markupsafe": {
            "hashes": [
                "sha256:05fb21170423db021895e1ea1e1f3ab3adb85d1c2333cbc2310f2a26bc77272e",
                "sha256:0a4e4a1aff6c7ac4cd55792abf96c915634c2b97e3cc1c7129578aa68ebd754e",
                "sha256:10bbfe99883db80bdbaff2dcf681dfc6533a614f700da1287707e8a5d78a8431",
                "sha256:134da1eca9ec0ae528110ccc9e48041e0828d79f24121a1a146161103c76e686",
                "sha256:14ff806850827afd6b07a5f32bd917fb7f45b046ba40c57abdb636674a8b559c",
                "sha256:1577735524cdad32f9f694208aa75e422adba74f1baee7551620e43a3141f559",
                "sha256:1b40069d487e7edb2676d3fbdb2b0829ffa2cd63a2ec26c4938b2d34391b4ecc",
                "sha256:1b8dd8c3fd14349433c79fa8abeb573a55fc0fdd769133baac1f5e07abf54aeb",
                "sha256:1f67c7038d560d92149c060157d623c542173016c4babc0c1913cca0564b9939",
                "sha256:282c2cb35b5b673bbcadb33a585408104df04f14b2d9b01d4c345a3b92861c2c",
                "sha256:2c1b19b3aaacc6e57b7e25710ff571c24d6c3613a45e905b1fde04d691b98ee0",
                "sha256:2ef12179d3a291be237280175b542c07a36e7f60718296278d8593d21ca937d4",
                "sha256:338ae27d6b8745585f87218a3f23f1512dbf52c26c28e322dbe54bcede54ccb9",
                "sha256:3c0fae6c3be832a0a0473ac912810b2877c8cb9d76ca48de1ed31e1c68386575",
                "sha256:3fd4abcb888d15a94f32b75d8fd18ee162ca0c064f35b11134be77050296d6ba",
                "sha256:42de32b22b6b804f42c5d98be4f7e5e977ecdd9ee9b660fda1a3edf03b11792d",
                "sha256:47d4f1c5f80fc62fdd7777d0d40a2e9dda0a05883ab11374334f6c4de38adffd",
                "sha256:504b320cd4b7eff6f968eddf81127112db685e81f7e36e75f9f84f0df46041c3",
                "sha256:525808b8019e36eb524b8c68acdd63a37e75714eac50e988180b169d64480a00",
                "sha256:56d9f2ecac662ca1611d183feb03a3fa4406469dafe241673d521dd5ae92a155",
                "sha256:5bbe06f8eeafd38e5d0a4894ffec89378b6c6a625ff57e3028921f8ff59318ac",
                "sha256:65c1a9bcdadc6c28eecee2c119465aebff8f7a584dd719facdd9e825ec61ab52",
                "sha256:68e78619a61ecf91e76aa3e6e8e33fc4894a2bebe93410754bd28fce0a8a4f9f",
                "sha256:69c0f17e9f5a7afdf2cc9fb2d1ce6aabdb3bafb7f38017c0b77862bcec2bbad8",
                "sha256:6b2b56950d93e41f33b4223ead100ea0fe11f8e6ee5f641eb753ce4b77a7042b",
                "sha256:715d3562f79d540f251b99ebd6d8baa547118974341db04f5ad06d5ea3eb8007",
                "sha256:787003c0ddb00500e49a10f2844fac87aa6ce977b90b0feaaf9de23c22508b24",
                "sha256:7ef3cb2ebbf91e330e3bb937efada0edd9003683db6b57bb108c4001f37a02ea",
                "sha256:8023faf4e01efadfa183e863fefde0046de576c6f14659e8782065bcece22198",
                "sha256:8758846a7e80910096950b67071243da3e5a20ed2546e6392603c096778d48e0",
                "sha256:8afafd99945ead6e075b973fefa56379c5b5c53fd8937dad92c662da5d8fd5ee",
                "sha256:8c41976a29d078bb235fea9b2ecd3da465df42a562910f9022f1a03107bd02be",
                "sha256:8e254ae696c88d98da6555f5ace2279cf7cd5b3f52be2b5cf97feafe883b58d2",
                "sha256:8f9293864fe09b8149f0cc42ce56e3f0e54de883a9de90cd427f191c346eb2e1",
                "sha256:9402b03f1a1b4dc4c19845e5c749e3ab82d5078d16a2a4c2cd2df62d57bb0707",
                "sha256:962f82a3086483f5e5f64dbad880d31038b698494799b097bc59c2edf392fce6",
                "sha256:9aad3c1755095ce347e26488214ef77e0485a3c34a50c5a5e2471dff60b9dd9c",
                "sha256:9dcdfd0eaf283af041973bff14a2e143b8bd64e069f4c383416ecd79a81aab58",
                "sha256:aa57bd9cf8ae831a362185ee444e15a93ecb2e344c8e52e4d721ea3ab6ef1823",
                "sha256:aa7bd130efab1c280bed0f45501b7c8795f9fdbeb02e965371bbef3523627779",
                "sha256:ab4a0df41e7c16a1392727727e7998a467472d0ad65f3ad5e6e765015df08636",
                "sha256:ad9e82fb8f09ade1c3e1b996a6337afac2b8b9e365f926f5a61aacc71adc5b3c",
                "sha256:af598ed32d6ae86f1b747b82783958b1a4ab8f617b06fe68795c7f026abbdcad",
                "sha256:b076b6226fb84157e3f7c971a47ff3a679d837cf338547532ab866c57930dbee",
                "sha256:b7ff0f54cb4ff66dd38bebd335a38e2c22c41a8ee45aa608efc890ac3e3931bc",
                "sha256:bfce63a9e7834b12b87c64d6b155fdd9b3b96191b6bd334bf37db7ff1fe457f2",
                "sha256:c011a4149cfbcf9f03994ec2edffcb8b1dc2d2aede7ca243746df97a5d41ce48",
                "sha256:c9c804664ebe8f83a211cace637506669e7890fec1b4195b505c214e50dd4eb7",
                "sha256:ca379055a47383d02a5400cb0d110cef0a776fc644cda797db0c5696cfd7e18e",
                "sha256:cb0932dc158471523c9637e807d9bfb93e06a95cbf010f1a38b98623b929ef2b",
                "sha256:cd0f502fe016460680cd20aaa5a76d241d6f35a1c3350c474bac1273803893fa",
                "sha256:ceb01949af7121f9fc39f7d27f91be8546f3fb112c608bc4029aef0bab86a2a5",
                "sha256:d080e0a5eb2529460b30190fcfcc4199bd7f827663f858a226a81bc27beaa97e",
                "sha256:dd15ff04ffd7e05ffcb7fe79f1b98041b8ea30ae9234aed2a9168b5797c3effb",
                "sha256:df0be2b576a7abbf737b1575f048c23fb1d769f267ec4358296f31c2479db8f9",
                "sha256:e09031c87a1e51556fdcb46e5bd4f59dfb743061cf93c4d6831bf894f125eb57",
                "sha256:e4dd52d80b8c83fdce44e12478ad2e85c64ea965e75d66dbeafb0a3e77308fcc",
                "sha256:f698de3fd0c4e6972b92290a45bd9b1536bffe8c6759c62471efaa8acb4c37bc",
                "sha256:fec21693218efe39aa7f8599346e90c705afa52c5b31ae019b2e57e8f6542bb2",
                "sha256:ffcc3f7c66b5f5b7931a5aa68fc9cecc51e685ef90282f4a82f0f5e9b704ad11"
            ],
            "markers": "python_version >= '3.7'",
            "version": "==2.1.3"
        },
        "sqlalchemy": {
            "hashes": [
                "sha256:0d3cab3076af2e4aa5693f89622bef7fa770c6fec967143e4da7508b3dceb9b9",
                "sha256:0dacf67aee53b16f365c589ce72e766efaabd2b145f9de7c917777b575e3659d",
                "sha256:10331f129982a19df4284ceac6fe87353ca3ca6b4ca77ff7d697209ae0a5915e",
                "sha256:14a6f68e8fc96e5e8f5647ef6cda6250c780612a573d99e4d881581432ef1669",
                "sha256:1b1180cda6df7af84fe72e4530f192231b1f29a7496951db4ff38dac1687202d",
                "sha256:29049e2c299b5ace92cbed0c1610a7a236f3baf4c6b66eb9547c01179f638ec5",
                "sha256:342d365988ba88ada8af320d43df4e0b13a694dbd75951f537b2d5e4cb5cd002",
                "sha256:420362338681eec03f53467804541a854617faed7272fe71a1bfdb07336a381e",
                "sha256:4344d059265cc8b1b1be351bfb88749294b87a8b2bbe21dfbe066c4199541ebd",
                "sha256:4f7a7d7fcc675d3d85fbf3b3828ecd5990b8d61bd6de3f1b260080b3beccf215",
                "sha256:555651adbb503ac7f4cb35834c5e4ae0819aab2cd24857a123370764dc7d7e24",
                "sha256:59a21853f5daeb50412d459cfb13cb82c089ad4c04ec208cd14dddd99fc23b39",
                "sha256:5fdd402169aa00df3142149940b3bf9ce7dde075928c1886d9a1df63d4b8de62",
                "sha256:605b6b059f4b57b277f75ace81cc5bc6335efcbcc4ccb9066695e515dbdb3900",
                "sha256:665f0a3954635b5b777a55111ababf44b4fc12b1f3ba0a435b602b6387ffd7cf",
                "sha256:6f9e2e59cbcc6ba1488404aad43de005d05ca56e069477b33ff74e91b6319735",
                "sha256:736ea78cd06de6c21ecba7416499e7236a22374561493b456a1f7ffbe3f6cdb4",
                "sha256:74b080c897563f81062b74e44f5a72fa44c2b373741a9ade701d5f789a10ba23",
                "sha256:75432b5b14dc2fff43c50435e248b45c7cdadef73388e5610852b95280ffd0e9",
                "sha256:75f99202324383d613ddd1f7455ac908dca9c2dd729ec8584c9541dd41822a2c",
                "sha256:790f533fa5c8901a62b6fef5811d48980adeb2f51f1290ade8b5e7ba990ba3de",
                "sha256:798f717ae7c806d67145f6ae94dc7c342d3222d3b9a311a784f371a4333212c7",
                "sha256:7c88f0c7dcc5f99bdb34b4fd9b69b93c89f893f454f40219fe923a3a2fd11625",
                "sha256:7d505815ac340568fd03f719446a589162d55c52f08abd77ba8964fbb7eb5b5f",
                "sha256:84daa0a2055df9ca0f148a64fdde12ac635e30edbca80e87df9b3aaf419e144a",
                "sha256:87d91043ea0dc65ee583026cb18e1b458d8ec5fc0a93637126b5fc0bc3ea68c4",
                "sha256:87f6e732bccd7dcf1741c00f1ecf33797383128bd1c90144ac8adc02cbb98643",
                "sha256:884272dcd3ad97f47702965a0e902b540541890f468d24bd1d98bcfe41c3f018",
                "sha256:8b8cb63d3ea63b29074dcd29da4dc6a97ad1349151f2d2949495418fd6e48db9",
                "sha256:91f7d9d1c4dd1f4f6e092874c128c11165eafcf7c963128f79e28f8445de82d5",
                "sha256:a2c69a7664fb2d54b8682dd774c3b54f67f84fa123cf84dda2a5f40dcaa04e08",
                "sha256:a3be4987e3ee9d9a380b66393b77a4cd6d742480c951a1c56a23c335caca4ce3",
                "sha256:a86b4240e67d4753dc3092d9511886795b3c2852abe599cffe108952f7af7ac3",
                "sha256:aa9373708763ef46782d10e950b49d0235bfe58facebd76917d3f5cbf5971aed",
                "sha256:b64b183d610b424a160b0d4d880995e935208fc043d0302dd29fee32d1ee3f95",
                "sha256:b801154027107461ee992ff4b5c09aa7cc6ec91ddfe50d02bca344918c3265c6",
                "sha256:bb209a73b8307f8fe4fe46f6ad5979649be01607f11af1eb94aa9e8a3aaf77f0",
                "sha256:bc8b7dabe8e67c4832891a5d322cec6d44ef02f432b4588390017f5cec186a84",
                "sha256:c51db269513917394faec5e5c00d6f83829742ba62e2ac4fa5c98d58be91662f",
                "sha256:c55731c116806836a5d678a70c84cb13f2cedba920212ba7dcad53260997666d",
                "sha256:cf18ff7fc9941b8fc23437cc3e68ed4ebeff3599eec6ef5eebf305f3d2e9a7c2",
                "sha256:d24f571990c05f6b36a396218f251f3e0dda916e0c687ef6fdca5072743208f5",
                "sha256:db854730a25db7c956423bb9fb4bdd1216c839a689bf9cc15fada0a7fb2f4570",
                "sha256:dc55990143cbd853a5d038c05e79284baedf3e299661389654551bd02a6a68d7",
                "sha256:e607cdd99cbf9bb80391f54446b86e16eea6ad309361942bf88318bcd452363c",
                "sha256:ecf6d4cda1f9f6cb0b45803a01ea7f034e2f1aed9475e883410812d9f9e3cfcf",
                "sha256:f2a159111a0f58fb034c93eeba211b4141137ec4b0a6e75789ab7a3ef3c7e7e3",
                "sha256:f37c0caf14b9e9b9e8f6dbc81bc56db06acb4363eba5a633167781a48ef036ed",
                "sha256:f5693145220517b5f42393e07a6898acdfe820e136c98663b971906120549da5"
            ],
            "markers": "python_version >= '3.7'",
            "version": "==2.0.25"
        },
        "typing-extensions": {
            "hashes": [
                "sha256:23478f88c37f27d76ac8aee6c905017a143b0b1b886c3c9f66bc2fd94f9f5783",
                "sha256:af72aea155e91adfc61c3ae9e0e342dbc0cba726d6cba4b6c72c1f34e47291cd"
            ],
            "markers": "python_version >= '3.8'",
            "version": "==4.9.0"
        },
        "werkzeug": {
            "hashes": [
                "sha256:507e811ecea72b18a404947aded4b3390e1db8f826b494d76550ef45bb3b1dcc",
                "sha256:90a285dc0e42ad56b34e696398b8122ee4c681833fb35b8334a095d82c56da10"
            ],
            "markers": "python_version >= '3.8'",
            "version": "==3.0.1"
        }
    },
    "develop": {}
}

