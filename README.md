# parametron_simulator

A parametron is a logic circuit element that applies the parametric excitation phenomenon, invented in 1954 by Eiichi Goto, a graduate student at the University of Tokyo. Currently, general logic circuits transmit information using voltage, whereas parametrons are characterized by transmitting information using the phase of AC signals. parametron_simulator is a browser-based simulator for simulating logic circuits composed of this parametron.

Usage:

You can edit the circuit using the tools on the left side of the screen.

Hand:
Drag anywhere on the screen to move the screen.
Clicking on a switch will invert the state of the switch.

Add Parametron:
Add a parametron with a click.

Add Switch:
Click to add a switch.
Switches can be flipped by clicking with the Hand tool.

Make Connection:
After clicking the parametron or switch that sends the signal, clicking another parametron will connect a wire to the input of the clicked parametron.
If you click on an empty place while extending the wire, the wire will relay there. A signal cannot be input to the switch.

Invert Connection:
You can invert the logic of an existing wire.

Bias:
You can bias the parametron positively or negatively.
A positively biased parametron behaves like a two-input OR gate and a negatively biased parametron behaves like a two-input AND gate.

Delete:
Remove parametrons or switches. Any wires associated with the deleted one are also deleted.

Del. Connection:
Delete existing wires.

Start/Stop:
You can start or stop the circuit simulation.

Load from Clips:
Load the clipboard circuit.

Save to Clip:
Copies all circuits in text format to the clipboard.


パラメトロンは、1954年に東京大学大学院の学生である後藤英一氏により発明された、パラメータ励振現象を応用した論理回路素子です。現在一般的な論理回路は電圧を用いて情報を伝達するのに対し、パラメトロンは交流信号の位相を用いて情報を伝達するのが特徴です。parametron_simulator は、このパラメトロンで構成された論理回路をシミュレートするために作られたブラウザベースのシミュレータです。

使い方：

画面左側にあるツールを用いて回路を編集できます。

Hand：
何もないところをドラッグすると、画面を移動します。
スイッチをクリックすると、スイッチの状態を反転させます。

Add Parametron：
クリックでパラメトロンを追加します。

Add Switch：
クリックでスイッチを追加します。
スイッチは、Handツールでクリックすると状態を反転できます。

Make Connection：
信号送出元のパラメトロンやスイッチをクリックしたのち、他のパラメトロンをクリックすると、クリックしたパラメトロンの入力にワイヤを接続できます。
配線を伸ばしている時に何もないところをクリックすると、配線がそこを中継するようになります。スイッチに対して信号を入力することはできません。

Invert Connection：
すでにあるワイヤの論理を反転させることができます。

Bias：
パラメトロンに正または負のバイアスをかけることができます。
正のバイアスをかけられたパラメトロンは２入力ORゲートのように振る舞い、負のバイアスをかけられたパラメトロンは２入力ANDゲートのように振る舞います。

Delete：
パラメトロンかスイッチを削除します。削除したものに関連づけられているワイヤも削除されます。

Del. Connection：
すでにあるワイヤを削除します。

Start / Stop：
回路のシミュレーションをスタートさせたり停止させたりできます。

Load from Clip：
クリップボードの回路を読み込みます。

Save to Clip：
クリップボードに全ての回路をテキスト形式でコピーします。




By Wakayama Takumi
