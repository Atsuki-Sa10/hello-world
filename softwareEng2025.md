ソフトウェアというのは情報を扱うプロダクトそのものでありプロダクトを提供する手段である  
ソフトウェアは定義として1.実行されることによって必要な特性、機能、性能を提供する命令語群。2.プログラムが適切に情報を扱うことを可能とするデータ構造 3.プログラムの操作や使用法を記述した情報 の3点がある.  
またソフトウェアの特徴として新しいっ環境や技術のおニーズを満たすよう適応しなければならない。新たなビジネス要求を実現するために強化されなければならない。より近代的なシステムやデータベースと相互運用するため拡張されなければならない。進化し続ける環境で実行可能となるよう、再構築されなければならないという点があり、ソフトウェア工学のゴールは進化論に基づく方法論を考え出すことである。新しいソフトウェアが古いシステムから構築され、すべては互換性を持ち、他システムと相互運用しなければならないとされている。  
またソフトウェア工学の定義はソフトウェアの開発運用メンテナンスに対するシステマティックで規律である定量化できるアプローチの適用つまりエンジニアリングの適用とされている。  
プラクティスの本質としてHookerの7原則が設けられている。  
ソフトウェア工学の必要性は大規模化と複雑さ、IT人材の不足、社会性と求められるミッション、不確実性の増大などの理由で説明される。  
ソフトウェアの一連の流れはソフトウェアライフサイクルとして説明される。まずニーズの発生や要求を具現化するための企画からソフトウェアが誕生し、次に実現する機能の範囲を決定しスコープを共有する要件定義を行う。次にこの要件定義で定めた要件定義書から設計書を作る設計段階に入る。ここでの設計書はWBSなどが用いられる。設計が終わったのちは制作フェーズへ入る。制作には自社で作成する内製と、外部へ委託する調達などが挙げられる。制作が終わるとテストとデバッグが行われる。基本的にバグのないソフトウェアは存在せず、あらかじめの早期発見対処が必要である。テストが終わった後は運用保守が必要になる。稼働後の不具合にも対応する必要があるからだ。  
ソフトウェア工学にはプロジェクトという考えが必要である。プロジェクトとは有期性と独自性を持つ業務の一つである。  
このプロジェクトというのは、今の立ち位置から目標へと進むフォアキャスティングではなく、定められた目標に向けて何が必要であるか計画して達成に向かうバックキャスティングと呼ばれるやり方で取り組む。この理由はフォアキャスティングでは目標に到達できない可能性や、目標から離れていってしまう可能性があるからである。そのためプロジェクトを始める際には目標を明確に設定する必要がある。ただし、この目標というのは適宜修正可能でありその軌道も修正できる。  
ソフトウェアは見える化をする必要がある。この見える化の手段として分析である。この一つにQCDがある。システムによってどれを優先するかを決める。ソフトウェアの評価は価値を測ることである。バグがないことの証明やソフトウェアのリリース時期の検討はHyrumの法則を想定する。バグの発生率は品質評価の1指標である。評価法にはファンクションポイント法もある。プログラミングに入る前にシステム規模の概算ができる。この概算によって新規開発か購入かの投資の決定の指標として使える。またソフトウェアの評価としてはユーザーの使い勝手もある。これには画面の視認性、操作性、入力補助、互換性、ガイダンスなどの要素が評価として用いられる。  
開発プロセスには複数のモデルがある。ウォーターフォールモデルは一つごとのステップが終わったら次のステップへと進み、基本的に前のステップに戻ることはない方式である。この方法は進捗管理が容易であるというメリットがあるが、後工程にしわ寄せが寄ってしまうというデメリットがある。スパイラルモデルはプログラム開発を小さなフェーズに分割し、フェーズごとにプロトタイプ、提案、評価、フィードバックという工程を繰り返す。このモデルはプロトタイプ作成に想定外の作業が発生するリスクを持ち合わせている。反復型開発プロセスはソフトウェアの機能で分割し、これを反復という単位で管理する。この方式は部分的に完成させていくので、顧客の要望に応えて変更しやすいという点がある。一方でメリットとして分割に伴う作業の増加や、全体像が見えづらいというデメリットがある。アジャイルプロセスはコンセプトとして変化の受容性や早いサイクル、シンプルな設計を取り入れた開発手法である。スクラムやカンバン、XPなどがこの種類である。これらの開発手法には一長一短があり、場面や顧客からの要求によって変えられるべきである。またこれらの複数を組み合わせたハイブリッド型の開発も多い。そしてアジャイルにおける人的リスクや計画駆動形における技術的課題、予測できない天災などの想定されるリスクをあらかじめ把握するリスク駆動型開発プロセスも大切である。  
プロジェクトが目標を達成し、必要な要素成果物を生成するため、プロジェクトチームが実行する作業を、要素成果物を主体に階層的に要素分解したものをWBSと呼ぶ。これはプロジェクトを細かい作業に分解し、作業順に並べた構成図である。WBSを作ることでスコープの明確化や作業を洗い出さすことができるなどのメリットがある。WBSの作り方はまずトップダウンアプローチかつバックキャスティングでスコープを明確化する。次に、データ収集、データ分析などの大きな作業をグルーピングする。そして、グルーピングした作業の相互関連を考え、最後にもれやダブりなしで各グループの作業を洗い出し図にまとめる。
