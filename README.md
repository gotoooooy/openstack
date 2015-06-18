# openstack
OpenStackというキーワードが聞こえてきたので穴あけ的なことをやってみる。

自分が知っているのは Havana(RDO) on RHEL6 まで。



OpenStackは今ではUbuntuでもRHELでも構築できる環境が整っていますが、もともとはUbuntuでしか動かない代物でした。

ところがGrizzlyあたりでRedHatが「RHEL版OpenStack作るわ＾＾」と言い出し、RDOというディストリ名でRHEL版OpenStackが誕生。



RDO_Juno以降ではRHEL6系は切り捨てられてしまっており、

Juno or kiloで組みたい -> RHEL7系で組め

RHEL6系でも組みたい -> IceHouse以前で組め

といったことになっています。



RHEL6 -> RHEL7については

ヒグマがどういうわけかパンダになりました

っていうくらいの変化、というより別物になっており敬遠してましたが、

いずれはスタンダードになってくることが明白、避けては通れない存在であります。

ここらで勉強も兼ねて　RDO Juno on CentOS 7を組んでみたいと思います。



そのうちChefで構成管理もやりながら運用できたら良いなとか思いますが、

まずは構築の基本的なところから。

