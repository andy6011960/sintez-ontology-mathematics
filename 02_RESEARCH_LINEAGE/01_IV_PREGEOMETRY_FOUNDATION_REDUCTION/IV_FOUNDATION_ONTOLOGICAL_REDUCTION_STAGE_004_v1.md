# IV FOUNDATION ONTOLOGICAL REDUCTION — STAGE 004
## Irreversibility, Return and a Minimal Operational Witness

**Version:** 1.0  
**Date:** 2026-07-16  
**Status:** Working research fixation / Ready for simulator design  
**Project:** IV Interpretation of Quantum Mechanics / Assemblage Ontology / Pregeometry  
**Method:** Ontological elimination under the Principle of Foundation

---

# ENGLISH VERSION

## 1. Purpose and epistemological boundary

Stage 003 revealed the ontological foundations of objects, morphisms, identity morphisms, composition, closure, associativity and identity laws.

Stage 004:

1. tests whether every morphism requires an inverse;
2. distinguishes return from strict inversion;
3. determines the status of group and groupoid;
4. derives a minimal operational witness distinguishing pure identity from nontrivial return.

Three levels remain explicitly separated:

- **ontological:** irreducible content obtained by elimination;
- **mathematical:** categorical and quantum-mechanical transcription;
- **operational:** measurable protocol and witness.

No equality at one level is automatically projected onto another.

---

## 2. Ontological test of inverse morphism

Let

\[
f:A\to B
\]

mathematically manifest Directed Ontological Connectedness.

Exclude completely:

\[
g:B\to A.
\]

Origin, object identities \(A\) and \(B\), space, relation, intrinsic description of \(A\to B\), and recognizability of the process all remain.

Operational inability to return to \(A\) does not destroy origin. Its recognizability is held by intrinsic description \(\mathcal D(f)\).

\[
\boxed{
f:A\to B
\centernot\Rightarrow
\exists g:B\to A
}.
\]

Inverse morphism is not universally required by Directed Ontological Connectedness.

---

## 3. Möbius return is not inversion

Möbius holds recognizability of origin through change. It does not require restoration of a former object identity.

\[
\text{Möbius}
\centernot\Rightarrow
B\to A.
\]

Even where \(g:B\to A\) exists, it may be an independent return process with its own intrinsic trajectory.

> Return of object identity is not cancellation of process origin.

---

## 4. Strict inversion and return endomorphism

Strict inversion requires:

\[
g\circ f=1_A,
\qquad
f\circ g=1_B.
\]

But composition does not erase intermediate objects or intrinsic process description.

\[
A\xrightarrow{f}B\xrightarrow{g}A
\]

holds the passage through \(B\), both directed parts and the full composite trajectory.

Define:

\[
u_A=g\circ f:A\to A.
\]

Its boundary identities coincide, but its intrinsic description is non-empty:

\[
u_A\not\equiv1_A.
\]

\(1_A\) is pure holding without new difference. \(u_A\) is a **return endomorphism** with process memory.

\[
\boxed{
g:B\to A
\centernot\Rightarrow
g=f^{-1}
}.
\]

> Object identity \(A\) is recognizable again, but return does not become absence of process.

---

## 5. Mathematical invertibility, group and groupoid

Strict invertibility may appear relative to an explicitly selected criterion of equivalence.

If a representation retains only initial and final boundaries while not distinguishing full trajectory:

\[
g\circ f\sim_{\partial}1_A.
\]

After quotienting:

\[
[g]\circ[f]=[1_A].
\]

This epistemic construction does not assert equality of intrinsic descriptions.

Therefore:

> Invertibility is relative to the criterion of distinguishability retained by the mathematical representation.

At the full provenance-preserving level:

\[
g\circ f=u_A\neq1_A.
\]

After controlled quotienting, one may obtain isomorphisms, a groupoid, or a group in the one-object case.

> Group is a special mathematical representation obtained under controlled loss of part of the distinguishability of process origin.

---

## 6. Quantum and experimental boundary

Standard quantum mechanics represents operatorial reversibility as:

\[
U^\dagger U=I.
\]

Ontological reduction distinguishes:

1. pure identity — no new difference;
2. nontrivial return — a trajectory \(U\) followed by \(U^\dagger\).

Candidate process distinction:

\[
\mathcal D(U^\dagger\circ U)
\not\equiv
\mathcal D(I).
\]

This does not assert different final states. It asserts different multi-time process descriptions.

The pair

\[
U^\dagger U=I,
\qquad
\mathcal D(U^\dagger\circ U)\not\equiv\mathcal D(I)
\]

marks the transition from ontology to an operationally testable hypothesis.

---

## 7. Minimal operational description

The minimal operational form of \(\mathcal D\) is a **one-slot process response** assigning an output state to one intermediate intervention \(\mathcal A\).

Pure identity:

\[
\mathcal D_I[\mathcal A](\rho)=\mathcal A(\rho).
\]

Let:

\[
\mathcal U(\rho)=U\rho U^\dagger,
\qquad
\mathcal U^\dagger(\rho)=U^\dagger\rho U.
\]

Nontrivial return:

\[
\mathcal D_U[\mathcal A](\rho)
=
\mathcal U^\dagger\circ\mathcal A\circ\mathcal U(\rho).
\]

For \(\mathcal A=\mathcal I\):

\[
\mathcal D_I[\mathcal I](\rho)
=
\mathcal D_U[\mathcal I](\rho)
=
\rho.
\]

For an intervention not invariant under conjugation by \(U\):

\[
\mathcal U^\dagger\circ\mathcal A\circ\mathcal U
\neq
\mathcal A,
\]

the processes are operationally distinguishable.

Primary process references:

- [Operational Markov condition for quantum processes](https://arxiv.org/abs/1801.09811)
- [Quantum Markov Order](https://arxiv.org/abs/1805.11341)
- [Theoretical framework for quantum networks](https://link.aps.org/doi/10.1103/PhysRevA.80.022339)

---

## 8. Minimal scalar witness

\[
\boxed{
W_{\mathcal D}
=
\frac12
\left\|
\mathcal D_U[\mathcal A](\rho)
-
\mathcal D_I[\mathcal A](\rho)
\right\|_1
}.
\]

- \(W_{\mathcal D}=0\): the selected intervention does not distinguish the processes;
- \(W_{\mathcal D}>0\): process structures are distinguishable;
- \(W_{\mathcal D}=1\): output states are perfectly distinguishable.

The minimal test requires one initial state, one intervention and one final binary measurement.

---

## 9. Minimal one-qubit protocol

Choose:

\[
\rho_0=|0\rangle\langle0|,
\qquad
U=H,
\qquad
\mathcal A=\mathcal Z.
\]

Pure identity:

\[
|0\rangle\xrightarrow{Z}|0\rangle,
\qquad
\mathcal D_I[Z](\rho_0)=|0\rangle\langle0|.
\]

Nontrivial return:

\[
|0\rangle
\xrightarrow{H}|+\rangle
\xrightarrow{Z}|-\rangle
\xrightarrow{H}|1\rangle,
\]

\[
\mathcal D_H[Z](\rho_0)=|1\rangle\langle1|.
\]

Therefore:

\[
\boxed{W_{\mathcal D}=1}.
\]

| Process | No intervention | With intermediate \(Z\) |
|---|---:|---:|
| Pure identity \(I\) | \(|0\rangle\) | \(|0\rangle\) |
| Return \(H^\dagger H\) | \(|0\rangle\) | \(|1\rangle\) |

---

## 10. Status and simulator boundary

The intermediate \(Z\):

- does not store a trajectory;
- requires no ancilla;
- performs no intermediate tomography;
- does not compute a metric from recorded history.

It asks:

> How does the process respond to the same intervention inside its boundaries?

Standard quantum mechanics also predicts the one-slot difference. The witness therefore does not by itself discriminate IV from standard process-tensor quantum mechanics.

Its significance is:

> An ontologically derived distinction has acquired a minimal operational form without an external trajectory journal.

\[
\boxed{
\text{ontological distinction}
\longrightarrow
\mathcal D
\longrightarrow
W_{\mathcal D}
\longrightarrow
\text{one-qubit protocol}
}.
\]

The minimal simulator must verify:

1. endpoint equality of \(I\) and \(H^\dagger H\) without intervention;
2. \(W_{\mathcal D}=1\) for \(Z\) versus \(H^\dagger ZH\);
3. state vectors, density matrices, trace distances, measurement probabilities and reproducibility metadata;
4. machine-readable JSON and a concise report.

Noise and alternative intervention families belong to later experimental extensions.

---

## 11. Current result

Stage 004 established:

1. Directed Ontological Connectedness does not universally require inverse morphisms.
2. Möbius return is not categorical inversion.
3. Return generally yields a nontrivial endomorphism with process memory.
4. Strict invertibility depends on a selected criterion of equivalence.
5. Group and groupoid are special quotient representations.
6. \(U^\dagger U=I\) does not require equality of multi-time descriptions.
7. A one-slot response is the minimal operational form of \(\mathcal D\).
8. \(W_{\mathcal D}\) distinguishes pure identity from nontrivial return.
9. The \(I\) versus \(H^\dagger H\) protocol probed with \(Z\) gives \(W_{\mathcal D}=1\).
10. The research is ready for minimal simulator implementation.

---

# RUSSIAN VERSION

## 1. Цель и эпистемологическая граница

Этап 003 выявил онтологические основания объектов, морфизмов, тождественных морфизмов, композиции, замкнутости, ассоциативности и законов тождества.

Этап 004:

1. проверяет необходимость обратного морфизма;
2. различает возвращение и строгое обращение;
3. определяет статус группы и группоида;
4. получает минимальный операционный свидетель различия чистого тождества и нетривиального возвращения.

Явно разделяются три уровня:

- **онтологический:** неустранимое содержание;
- **математический:** категориальная и квантовая транскрипция;
- **операционный:** измеримый протокол.

Равенство одного уровня не переносится автоматически на другой.

---

## 2. Онтологический тест обратного морфизма

Пусть:

\[
f:A\to B
\]

математически проявляет направленную онтологическую связность.

Полностью исключаем:

\[
g:B\to A.
\]

Происхождение, тождества \(A\) и \(B\), пространство, отношение, внутреннее описание \(A\to B\) и распознаваемость процесса сохраняются.

Невозможность вернуться к \(A\) не уничтожает происхождение. Его распознаваемость удерживает \(\mathcal D(f)\).

\[
\boxed{
f:A\to B
\centernot\Rightarrow
\exists g:B\to A
}.
\]

Обратный морфизм не является универсальным требованием направленной онтологической связности.

---

## 3. Мёбиусное возвращение не является обращением

Мёбиус удерживает распознаваемость происхождения через изменение, но не требует восстановления прежнего объектного тождества.

\[
\text{Мёбиус}
\centernot\Rightarrow
B\to A.
\]

Даже существующее \(g:B\to A\) может быть самостоятельным процессом с собственной траекторией.

> Возвращение объектного тождества не является уничтожением происхождения процесса.

---

## 4. Строгое обращение и эндоморфизм возвращения

Строгое обращение требует:

\[
g\circ f=1_A,
\qquad
f\circ g=1_B.
\]

Но композиция не стирает промежуточные объекты и внутреннее описание.

\[
A\xrightarrow{f}B\xrightarrow{g}A
\]

удерживает прохождение через \(B\) и полную составную траекторию.

\[
u_A=g\circ f:A\to A.
\]

Границы совпадают, но описание не пусто:

\[
u_A\not\equiv1_A.
\]

\(1_A\) — чистое удержание без нового различия. \(u_A\) — **эндоморфизм возвращения** с памятью процесса.

\[
\boxed{
g:B\to A
\centernot\Rightarrow
g=f^{-1}
}.
\]

> Тождество \(A\) снова распознаваемо, но возвращение не становится отсутствием процесса.

---

## 5. Обратимость, группа и группоид

Строгая обратимость возникает относительно выбранного критерия эквивалентности.

Если представление удерживает только границы:

\[
g\circ f\sim_{\partial}1_A.
\]

После факторизации:

\[
[g]\circ[f]=[1_A].
\]

Это эпистемическое построение, не равенство внутренних описаний.

> Обратимость относительна критерию различимости, сохраняемому представлением.

На полном уровне:

\[
g\circ f=u_A\neq1_A.
\]

После контролируемой факторизации возможны изоморфизмы, группоид и группа в однообъектном случае.

> Группа является специальным математическим представлением при контролируемой утрате части различимости происхождения процесса.

---

## 6. Квантовая и экспериментальная граница

Стандартная квантовая механика записывает:

\[
U^\dagger U=I.
\]

Онтология различает:

1. чистое тождество;
2. нетривиальное возвращение \(U\), затем \(U^\dagger\).

\[
\mathcal D(U^\dagger\circ U)
\not\equiv
\mathcal D(I).
\]

Это различие много-временных описаний, а не конечных состояний.

Пара

\[
U^\dagger U=I,
\qquad
\mathcal D(U^\dagger\circ U)\not\equiv\mathcal D(I)
\]

обозначает переход к операционно проверяемой гипотезе.

---

## 7. Минимальное операционное описание

Минимальная форма \(\mathcal D\) — **однослотовый отклик процесса** на вмешательство \(\mathcal A\).

Чистое тождество:

\[
\mathcal D_I[\mathcal A](\rho)=\mathcal A(\rho).
\]

\[
\mathcal U(\rho)=U\rho U^\dagger,
\qquad
\mathcal U^\dagger(\rho)=U^\dagger\rho U.
\]

Нетривиальное возвращение:

\[
\mathcal D_U[\mathcal A](\rho)
=
\mathcal U^\dagger\circ\mathcal A\circ\mathcal U(\rho).
\]

Для \(\mathcal A=\mathcal I\):

\[
\mathcal D_I[\mathcal I](\rho)
=
\mathcal D_U[\mathcal I](\rho)
=
\rho.
\]

Если:

\[
\mathcal U^\dagger\circ\mathcal A\circ\mathcal U
\neq
\mathcal A,
\]

процессы различимы.

Источники:

- [Operational Markov condition for quantum processes](https://arxiv.org/abs/1801.09811)
- [Quantum Markov Order](https://arxiv.org/abs/1805.11341)
- [Theoretical framework for quantum networks](https://link.aps.org/doi/10.1103/PhysRevA.80.022339)

---

## 8. Минимальный свидетель

\[
\boxed{
W_{\mathcal D}
=
\frac12
\left\|
\mathcal D_U[\mathcal A](\rho)
-
\mathcal D_I[\mathcal A](\rho)
\right\|_1
}.
\]

- \(W_{\mathcal D}=0\): вмешательство не различает процессы;
- \(W_{\mathcal D}>0\): структуры процессов различимы;
- \(W_{\mathcal D}=1\): выходные состояния идеально различимы.

---

## 9. Однокубитный протокол

\[
\rho_0=|0\rangle\langle0|,
\qquad
U=H,
\qquad
\mathcal A=\mathcal Z.
\]

Чистое тождество:

\[
|0\rangle\xrightarrow{Z}|0\rangle,
\qquad
\mathcal D_I[Z](\rho_0)=|0\rangle\langle0|.
\]

Возвращение:

\[
|0\rangle
\xrightarrow{H}|+\rangle
\xrightarrow{Z}|-\rangle
\xrightarrow{H}|1\rangle,
\]

\[
\mathcal D_H[Z](\rho_0)=|1\rangle\langle1|.
\]

\[
\boxed{W_{\mathcal D}=1}.
\]

| Процесс | Без вмешательства | С промежуточным \(Z\) |
|---|---:|---:|
| Чистое тождество \(I\) | \(|0\rangle\) | \(|0\rangle\) |
| Возвращение \(H^\dagger H\) | \(|0\rangle\) | \(|1\rangle\) |

---

## 10. Статус и граница симулятора

\(Z\) не записывает траекторию, не требует анциллы и не выполняет промежуточную томографию. Оно задаёт вопрос:

> Как процесс отвечает на одинаковое вмешательство внутри своих границ?

Стандартная КМ также предсказывает это различие. Свидетель сам по себе не отделяет IV от process-tensor КМ.

Его значение:

> Онтологически выведенное различие получило минимальную операционную форму без внешнего журнала.

\[
\boxed{
\text{онтологическое различие}
\longrightarrow
\mathcal D
\longrightarrow
W_{\mathcal D}
\longrightarrow
\text{однокубитный протокол}
}.
\]

Минимальный симулятор должен проверить:

1. равенство конечных состояний \(I\) и \(H^\dagger H\) без вмешательства;
2. \(W_{\mathcal D}=1\) для \(Z\) и \(H^\dagger ZH\);
3. векторы состояний, матрицы плотности, следовые расстояния и вероятности;
4. JSON, отчёт и метаданные воспроизводимости.

Шум и альтернативные семейства вмешательств относятся к расширениям.

---

## 11. Текущий результат

Этап 004 установил:

1. Направленная онтологическая связность не требует обратного морфизма.
2. Мёбиусное возвращение не является категориальным обращением.
3. Возвращение даёт нетривиальный эндоморфизм с памятью процесса.
4. Строгая обратимость зависит от критерия эквивалентности.
5. Группа и группоид являются специальными факторизованными представлениями.
6. \(U^\dagger U=I\) не требует равенства много-временных описаний.
7. Однослотовый отклик — минимальная операционная форма \(\mathcal D\).
8. \(W_{\mathcal D}\) различает чистое тождество и нетривиальное возвращение.
9. Протокол \(I\) против \(H^\dagger H\), зондируемый \(Z\), даёт \(W_{\mathcal D}=1\).
10. Исследование готово к реализации на симуляторе.

---

**End of document**
