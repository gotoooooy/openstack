# openstack
OpenStackというキーワードが聞こえてきたので穴あけ的なことをやってみる。

自分が知っているのは Havana(RDO) on RHEL6 まで。


OpenStackは今ではUbuntuでもRHELでも構築できる環境が整っていますが、もともとはUbuntuでしか動かない代物でした。

ところがGrizzlyあたりでRedHatが「RHEL版OpenStack作るわ＾＾」と言い出し、RDOというディストリ名でRHEL版OpenStackが誕生。


現在、RDO_JunoではRHEL6系は切り捨てられてしまっており、

最新Junoで組みたい -> RHEL7系で組め

RHEL6系でも組みたい -> Junoは諦めろ。1世代前のIceHouseで組め

といったことになっています。


ざっくり調べたところ、RHEL6 -> RHEL7でものすごい色々と代わってしまっており、

もはや別物じゃないかという感覚でしたのでRHEL7は手が出ないでいたのですが、

いずれはスタンダードになってくると思われますので、

勉強も兼ねて　RDO Juno on CentOS 7を組んでみたいと思います。

