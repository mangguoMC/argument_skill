# 边界情形与示例（Boundary Cases and Examples）

按问题查阅相应条目。示例原文均为自拟材料。

## 定义与隐含前提（Definitions and Implicit Premises）

- 多个释义若有共同内容，先写最小共同含义，再写足以改变推导的候选。若同一词在原文中没有可确认的共同含义，保留其不同用法。定义中的实质性理论主张仍有其原来的证成地位。分析者自行约定的含义只出现在标明归属的分析分支中。
- 从「苏格拉底是人」推出「苏格拉底会死」时，若语境表明理由是人的普遍死亡性，可将「所有人都会死」作为隐含前提。若语境只支持个别条件，则可列与苏格拉底有关的条件。若文本仅给出这两个命题而缺乏可辨认的理由，合乎形式的条件句本身不足以确立作者采用了它。
- 若候选仅用于检验一种可能的重构，在该分支标注「隐含前提（Implicit Premise），候选归属未定（Tentative Attribution）」，并说明其文本依据或缺少依据之处。

## 上游依据与直接证成（Upstream Grounds and Direct Justification）

> 我直接意识到自己此刻正在经历某种体验。我现在据前文命题 Q 进行推导。Q 已证明凡处于体验中的主体都满足条件 K。因此我满足 K。

- **P1** 我此刻正在经历某种体验。［明确前提（Explicit Premise）。证成方式（Mode of Justification）为作者诉诸直接意识（Direct Awareness）。］
- **P2** 凡处于体验中的主体都满足条件 K。［明确前提（Explicit Premise）。援引（Reference）为前文命题 Q。如果未提供前文，标注未核验（Unverified）。］
- **C1** 我满足 K。依据（Grounds）为 P1、P2。推理类型（Inference Type）为演绎（Deduction）。推理规则（Inference Rule）为全称实例化（Universal Instantiation）与肯定前件式（Modus Ponens）。论证结构（Argument Structure）为联合论证（Linked Argument）。

若找到 Q 的证明，先核对实际命题、适用条件及与此处所引内容的匹配程度。已将 Q 拆为上游结论时，直接用其 `C` 替代 P2，保留上游支持状态。P1 的直接证成与 C1 的演绎推导各自保留。若直接证成的命题本身是论证目标，使用 `C` 并标明依据（Grounds）为无推论性依据（No Inferential Grounds）、推理类型（Inference Type）为非推论性证成（Non-inferential Justification）、推理规则（Inference Rule）和论证结构（Argument Structure）均不适用（Not Applicable）。同时说明作者诉诸的支持方式（Support）。

## 局部假设与撤销（Local Assumptions and Discharge）

> 所有物体均具有空间延展性。对象 X 不具有空间延展性。因此 X 不是物体。

- **P1** 所有物体均具有空间延展性。［明确前提（Explicit Premise）］
- **P2** 对象 X 不具有空间延展性。［明确前提（Explicit Premise）］
- **A1** 假设 X 是物体。［作用域开始（Scope Opens）］
  - **C1** X 具有空间延展性。依据（Grounds）为 P1、A1。推理类型（Inference Type）为演绎（Deduction）。推理规则（Inference Rule）为全称实例化（Universal Instantiation）与肯定前件式（Modus Ponens）。论证结构（Argument Structure）为联合论证（Linked Argument）。
  - **C2** X 同时具有和不具有空间延展性。依据（Grounds）为 C1、P2。推理类型（Inference Type）为演绎（Deduction）。推理规则（Inference Rule）为合取引入（Conjunction Introduction）。论证结构（Argument Structure）为链式论证（Serial Argument）和联合论证（Linked Argument）。
- **C3** X 不是物体。［作用域结束（Scope Closes），撤销 A1。］依据（Grounds）为从 A1 到 C2 的局部推导及其外部依赖 P1、P2。推理类型（Inference Type）为演绎（Deduction）。推理规则（Inference Rule）为否定引入（Negation Introduction）。论证结构（Argument Structure）为链式论证（Serial Argument）。

证明级拆解时，在 C1 前分别写出全称实例化得到的条件命题和肯定前件式应用。处理嵌套假设时，撤销内层假设后仍保留尚未撤销的外层假设。条件证明与分情况讨论同样要核对局部结论可否用于外层。

## 无效形式与独立支持（Invalid Forms and Independent Support）

> 如果理论 T 为真，现象 E 就会出现。现在 E 出现了，所以我已经证明 T 为真。若 T 为真，Q 就为真，因此 Q 为真。另一个独立理由是已经观测到 R，而且只要 R 出现，Q 就为真。

- **P1** 若 T 为真，则 E 出现。［明确前提（Explicit Premise）］
- **P2** E 出现。［明确前提（Explicit Premise）］
- **C1** T 为真。依据（Grounds）为 P1、P2。推理类型（Inference Type）为意图作演绎推理（Deduction）。推理规则（Inference Rule）处注明该形式无有效规则可用。意图推理（Intended Inference）为演绎证明（Deductive Proof），实际推理（Actual Inference）为肯定后件谬误（Affirming the Consequent）。论证结构（Argument Structure）为联合论证（Linked Argument）。推导缺口（Inferential Gap）记为 G1。
- **P3** 若 T 为真，则 Q 为真。［明确前提（Explicit Premise）］
- **P4** 已观测到 R 出现。［明确前提（Explicit Premise）］
- **P5** 若 R 出现，则 Q 为真。［明确前提（Explicit Premise）］
- **C2** Q 为真。论证结构（Argument Structure）为汇聚论证（Convergent Argument）。
  - 路线一的依据（Grounds）为 C1、P3。推理类型（Inference Type）为演绎（Deduction），推理规则（Inference Rule）为肯定前件式（Modus Ponens）。该路线为链式论证（Serial Argument）和联合论证（Linked Argument），局部有效（Locally Valid），整体支持（Global Support）继承 G1。相对于 P3，须另行接受 C1 才能由此路线推出 C2。
  - 路线二的依据（Grounds）为 P4、P5。推理类型（Inference Type）为演绎（Deduction），推理规则（Inference Rule）为肯定前件式（Modus Ponens），该路线为联合论证（Linked Argument），相对于 P4、P5 的支持独立于 G1。

原文的「已经证明」支持将 C1 的意图标为演绎证明。若另一个文本将 E 作为 T 的最佳解释证据，应据该文本检查实际溯因推理。

## 非演绎支持与结构（Non-deductive Support and Structure）

> 在所观察的多次案例中，改变脑活动伴随着某类体验发生变化。因此，在相似条件下，改变脑活动通常会伴随该类体验变化。

- **P1** 在所观察的多次案例中，改变脑活动伴随着某类体验发生变化。［明确前提（Explicit Premise）］
- **C1** 在相似条件下，改变脑活动通常会伴随该类体验变化。依据（Grounds）为 P1。推理类型（Inference Type）为归纳（Induction）。推理规则（Inference Rule）为枚举归纳（Enumerative Induction）。论证结构（Argument Structure）为单一论证（Simple Argument）。支持程度（Degree of Support）取决于样本及条件的相似性。

按材料选用推理类型。规则可以来自演绎、归纳、溯因、类比、因果、证言、实践与规范、模态、反事实或其他确有依据的方式。若推导依赖特定逻辑系统或条件，标明该依赖。分析结构时，联合依据可记作 `(P1 + P2) → C1`。汇聚路线可分别记作 `P1 → C1` 与 `(P2 + P3) → C1`。同一组依据支持多个结论时，在各结论注明共享依据和相关 `C`，并标注发散论证（Divergent Argument）。
