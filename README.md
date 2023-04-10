# D3 Proyecto
## Español 
 ![Image](https://cdn.freecodecamp.org/platform/universal/fcc_meta_1920X1080-indigo.png)

### 🧐 Contexto
En medio del aprendizaje de FreeCodeCamp se nos proponia el siguiente proyecto...
### 🤔 El problema
Objetivo: crea una app que sea funcionalmente similar a esta: https://bar-chart.freecodecamp.rocks.

Completa las historias de usuario a continuación y obtén todas las pruebas para aprobar. Utiliza cualquier librería o API que necesites. Dale tu propio estilo.

Puedes utilizar HTML, JavaScript, CSS y la librería D3 de visualización basada en svg. Las pruebas requieren que los ejes se generen utilizando la propiedad de eje D3, que genera automáticamente marcas a lo largo del eje. Estas marcas son necesarias para pasar las pruebas D3, ya que sus posiciones se utilizan para determinar la alineación de los elementos gráficos. Encontrarás información sobre cómo generar ejes en https://github.com/d3/d3/blob/master/API.md#axes-d3-axis. Los elementos DOM necesarios se consultan en el momento de cada prueba. Si usas un framework frontend (como por ejemplo Vue), los resultados de la prueba pueden ser inexactos para el contenido dinámico. Esperamos poder adaptarlos eventualmente, pero por ahora estos frameworks no son soportados por los proyectos con D3.

#### Historia de usuario #1: Mi gráfica debe tener un título con su correspondiente id="title".

#### Historia de usuario #2: Mi gráfica debe tener un elemento g en el eje-x con su correspondiente id="x-axis".

#### Historia de usuario #3: Mi gráfica debe tener un elemento g en el eje-y con su correspondiente id="y-axis".

#### Historia de usuario #4: Ambos ejes debe contener múltiples etiquetas de marca, cada uno con su correspondiente class="tick".

#### Historia de usuario #5: Mi gráfica debe tener un elemento rect por cada punto de datos con su correspondiente class="bar" mostrando los datos.

#### Historia de usuario nº 6: Cada .bar debe tener las propiedades data-date y data-gdp que contienen los valores date y GDP.

#### Historia de usuario nº 7: Las propiedades .bar de los elementos data-date deben coincidir con el orden de los datos proporcionados.

#### Historia de usuario nº 8: Las propiedades .bar de los elementos data-gdp deben coincidir con el orden de los datos proporcionados.

#### Historia de usuario nº 9: La altura de cada elemento .bar debe representar con exactitud el GDP correspondiente a los datos.

#### Historia de usuario nº 10: El atributo data-date y su correspondiente elemento .bar deben alinearse con el valor correspondiente en el eje x.

#### Historia de usuario nº 11: El atributo data-gdp y su correspondiente elemento .bar deben alinearse con el valor correspondiente en el eje y.

#### Historia de usuario #12: Puedo pasar el ratón por encima de un área y ver un cuadro emergente con su correspondiente id="tooltip" que muestra más información acerca del área.

#### Historia de usuario #13: Mi cuadro emergente debe tener una propiedad data-date que corresponda con el data-date del área activa.

Aquí está el conjunto de datos que necesitarás para completar este proyecto: https://raw.githubusercontent.com/freeCodeCamp/ProjectReferenceData/master/GDP-data.json

Puedes crear tu proyecto usando esta plantilla, haciendo clic en Save para crear tu propio proyecto CodePen. O puedes utilizar este enlace CDN para ejecutar las pruebas en cualquier entorno que desees: https://cdn.freecodecamp.org/testable-projects-fcc/v1/bundle.js.

Una vez que hayas terminado, envía la URL de tu proyecto funcional con todas las pruebas pasadas.

### ⌨⌨ Tecnologias Usadas...

<code><img height="35" src="https://raw.githubusercontent.com/github/explore/80688e429a7d4ef2fca1e82350fe8e3517d3494d/topics/css/css.png"></code>
<code><img height="35" src="https://raw.githubusercontent.com/github/explore/80688e429a7d4ef2fca1e82350fe8e3517d3494d/topics/html/html.png"></code>
<code><img height="35" src="https://raw.githubusercontent.com/github/explore/80688e429a7d4ef2fca1e82350fe8e3517d3494d/topics/javascript/javascript.png"></code>
<code><img height="35" src="https://raw.githubusercontent.com/d3/d3-logo/master/d3.png"></code>

## English

![Image](https://cdn.freecodecamp.org/platform/universal/fcc_meta_1920X1080-indigo.png)

### 🧐 Context
In the midst of learning about FreeCodeCamp, the following project was proposed to us...
### 🤔 The problem
Goal: Create an app that is functionally similar to this: https://bar-chart.freecodecamp.rocks.

Complete the user stories below and get all the tests to pass. Use any library or API you need. Give it your own style.

You can use HTML, JavaScript, CSS and the D3 svg-based visualization library. The tests require the axes to be generated using the D3 axis property, which automatically generates marks along the axis. These marks are required to pass the D3 tests, as their positions are used to determine the alignment of graphic elements. You can find information on how to generate axes at https://github.com/d3/d3/blob/master/API.md#axes-d3-axis. The required DOM elements are queried at the time of each test. If you use a frontend framework (such as Vue), the test results may be inaccurate for dynamic content. We hope to be able to port them eventually, but for now these frameworks are not supported by D3 projects.

#### User Story #1: My graph must have a title with a corresponding id="title".

#### User Story #2: My graph should have a g element on the x-axis with its corresponding id="x-axis".

#### User Story #3: My graph should have a g element on the y-axis with a corresponding id="y-axis".

#### User Story #4: Both axes should contain multiple tick tags, each with a corresponding class="tick".

#### User Story #5: My graph should have a rect element for each data point with its corresponding class="bar" showing the data.

#### User Story #6: Each .bar should have data-date and data-gdp properties that contain the date and GDP values.

#### User Story #7: The .bar properties of data-date elements must match the order of the supplied data.

#### User Story #8: The .bar properties of data-gdp elements must match the order of the supplied data.

#### User Story #9: The height of each .bar element must accurately represent the GDP corresponding to the data.

#### User Story #10: The data-date attribute and its corresponding .bar element must align with the corresponding value on the x-axis.

#### User Story #11: The data-gdp attribute and its corresponding .bar element should align with the corresponding value on the y-axis.

#### User Story #12: I can hover my mouse over an area and see a popup box with its corresponding id="tooltip" showing more information about the area.

#### User Story #13: My popup should have a data-date property that corresponds to the data-date of the active area.

Here is the data set you will need to complete this project: https://raw.githubusercontent.com/freeCodeCamp/ProjectReferenceData/master/GDP-data.json

You can create your project using this template, by clicking Save to create your own CodePen project. Or you can use this CDN link to run the tests in any environment you want: https://cdn.freecodecamp.org/testable-projects-fcc/v1/bundle.js.

Once you're done, submit the URL of your working project with all the tests passed.

### ⌨⌨ Used Technologies...

<code><img height="35" src="https://raw.githubusercontent.com/github/explore/80688e429a7d4ef2fca1e82350fe8e3517d3494d/topics/css/css.png"></code>
<code><img height="35" src="https://raw.githubusercontent.com/github/explore/80688e429a7d4ef2fca1e82350fe8e3517d3494d/topics/html/html.png"></code>
<code><img height="35" src="https://raw.githubusercontent.com/github/explore/80688e429a7d4ef2fca1e82350fe8e3517d3494d/topics/javascript/javascript.png"></code>
<code><img height="35" src="https://raw.githubusercontent.com/d3/d3-logo/master/d3.png"></code>

## Japones

![Image](https://cdn.freecodecamp.org/platform/universal/fcc_meta_1920X1080-indigo.png)

### 🧐 コンテキスト
FreeCodeCamp について学んでいる最中に、次のプロジェクトが提案されました...
### 🤔 問題
目標: https://bar-chart.freecodecamp.rocks と機能的に類似したアプリを作成します。

以下のユーザー ストーリーを完了し、すべてのテストに合格してください。 必要なライブラリまたは API を使用します。 あなた自身のスタイルを与えてください。

HTML、JavaScript、CSS、および D3 svg ベースの視覚化ライブラリを使用できます。 テストでは、軸に沿ってマークを自動的に生成する D3 軸プロパティを使用して軸を生成する必要があります。 これらのマークは、グラフィック要素の配置を決定するためにその位置が使用されるため、D3 テストに合格する必要があります。 軸の生成方法に関する情報は、https://github.com/d3/d3/blob/master/API.md#axes-d3-axis にあります。 必要な DOM 要素は、各テスト時に照会されます。 フロントエンド フレームワーク (Vue など) を使用する場合、動的コンテンツのテスト結果が不正確になる可能性があります。 最終的には移植できるようにしたいと考えていますが、現時点ではこれらのフレームワークは D3 プロジェクトでサポートされていません。

#### ユーザー ストーリー #1: 私のグラフには、id="title" に対応するタイトルが必要です。

#### ユーザー ストーリー #2: 私のグラフには、対応する id="x-axis" を持つ x 軸に g 要素が必要です。

#### ユーザー ストーリー #3: 私のグラフには、対応する id="y-axis" を持つ y 軸に g 要素が必要です。

#### ユーザー ストーリー #4: 両方の軸に、それぞれ対応する class="tick" を持つ複数の目盛りタグを含める必要があります。

#### ユーザー ストーリー #5: 私のグラフには、データを示す対応する class="bar" を持つ各データ ポイントの rect 要素が必要です。

#### ユーザー ストーリー #6: 各 .bar には、日付と GDP の値を含む data-date および data-gdp プロパティが必要です。

#### ユーザー ストーリー #7: data-date 要素の .bar プロパティは、提供されたデータの順序と一致する必要があります。

#### ユーザー ストーリー #8: data-gdp 要素の .bar プロパティは、提供されたデータの順序と一致する必要があります。

#### ユーザー ストーリー #9: 各 .bar 要素の高さは、データに対応する GDP を正確に表す必要があります。

#### ユーザー ストーリー #10: data-date 属性とそれに対応する .bar 要素は、x 軸の対応する値と一致する必要があります。

#### ユーザー ストーリー #11: data-gdp 属性とそれに対応する .bar 要素は、y 軸の対応する値と一致する必要があります。

#### ユーザー ストーリー #12: 領域にマウスを合わせると、対応する id="tooltip" を含むポップアップ ボックスが表示され、その領域に関する詳細情報が表示されます。

#### ユーザー ストーリー #13: 私のポップアップには、アクティブな領域のデータ日付に対応するデータ日付プロパティが必要です。

このプロジェクトを完了するために必要なデータ セットは次のとおりです: https://raw.githubusercontent.com/freeCodeCamp/ProjectReferenceData/master/GDP-data.json

このテンプレートを使用してプロジェクトを作成するには、[保存] をクリックして独自の CodePen プロジェクトを作成します。 または、この CDN リンクを使用して、必要な環境でテストを実行できます: https://cdn.freecodecamp.org/testable-projects-fcc/v1/bundle.js。

完了したら、すべてのテストに合格した作業中のプロジェクトの URL を送信します。

### ⌨⌨ 使用されたテクノロジー...

<code><img height="35" src="https://raw.githubusercontent.com/github/explore/80688e429a7d4ef2fca1e82350fe8e3517d3494d/topics/css/css.png"></code>
<code><img height="35" src="https://raw.githubusercontent.com/github/explore/80688e429a7d4ef2fca1e82350fe8e3517d3494d/topics/html/html.png"></code>
<code><img height="35" src="https://raw.githubusercontent.com/github/explore/80688e429a7d4ef2fca1e82350fe8e3517d3494d/topics/javascript/javascript.png"></code>
<code><img height="35" src="https://raw.githubusercontent.com/d3/d3-logo/master/d3.png"></code>
