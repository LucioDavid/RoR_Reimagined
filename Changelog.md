v0.1

# General Changes

## Units

### Archery Range

Bowman:
- Now costs 40 Food and 20 Gold, the same as the Improved Bowman and the Composite Bowman.

Improved Bowman:
- Is now an upgrade to the Bowman.
- Has 5 base attack instead of 4.
- Hotkey for unit creation and unit upgrade adjusted.

Composite Bowman:
- Moved to the Iron Age (IV).
- Has 7 base attack instead of 5.
- Hotkey for unit creation and unit upgrade adjusted.

### Barracks

Slinger:
- No longer has a bonus damage against Archers.
- Gain a bonus damage against Infantry.

Elite Slinger (NEW):
- Upgrade to the Slinger avaliable at the Bronze Age (III).

### Stable

Horseman (NEW):
- Available from the Tool Age (II).
- Regional replacement to the Chariot-line.
- No splash damage.
- Less damage, but cheaper.
- Bonus vs Temple Units and Siege Units.

Light Cavalry (NEW):
- Available from the Bronze Age (III).
- Upgrade to the Horseman.

Raider (NEW):
- Available from the Iron Age (IV).
- Upgrade to the Light Cavalry.

Scout:
- Reworked to be better at scouting.

# TODOs em geral

- [ ]. Remover pre-requisite "Improved Bow" da Tech Tree UI.
- [ ]. Revisar distribuição do Slinger e Elite Slinger (incluir na Tech Tree UI)
- [ ]. (Bowman): revisar strings (precisa incluir upgrade).
- [ ]. (Bowman): revisar strings de bowman-line e improved bowman-line.
- [ ]. (Improved Bowman): Revisar strings como upgrade em vez de base da linha.
- [ ]. (Improved Bowman): Revisar custo de upgrade.
- [ ]. (Composite Bowman): Revisar custo de upgrade.
- [ ]. (Slinger): ajustar os status para incluir o novo bônus
- [ ]. (Slinger): ajustar menções em strings como counter de arqueiros.
- [ ]. (Slinger): mencionar em strings como counter em todas as infantarias.
- [ ]. (Elite Slinger): corrigir projétil --> criei e usei um novo projétil duplicando do Chronicles e ainda não funcionou. Reverti.
- [ ]. (Elite Slinger): ajustar os status
- [ ]. (Scout): ajustar status para que de fato seja melhor para explorar (mais visão em geral, revisar velocidade).
- [ ]. Revisar parte lógica das Tech Trees (effect).
- [ ]. Revisar parte visual das Tech Trees (json).
- [ ]. Revisar status da Horseman-line (inclusive velocidade de movimento).
- [ ]. Revisar bônus de civ's e team bônus.
- [ ]. Conferir aplicação de bônus sobre unidades novas.
- [ ]. Verificar possibilidade de novos bônus para unidades novas.
- [ ]. Verificar possibilidade de aproveitar gráficos de ataque alternativos. Várias unidades têm os gráficos prontos,
       seria uma pena não utilizar, e dava para deixar mais diferenciadas as civilizações.
- [ ]. Adicionar bônus contra Spearman para várias unidades.
- [ ]. Revisar velocidade de movimento da linha do Spearman.
- [ ]. Tornar mais caro o upgrade Improved Bowman, pois dá mais alcance.
- [ ]. Tornar mais caro o upgrade Elite Skirmisher, pois dá mais alcance.
- [ ]. Revisar Elephant Archer. Acho que será necessário aumentar o ataque para 7.
- [x]. Future Available Units da Skirmisher-line.
- [x]. (Elite Slinger) Corrigir som de morte (está com o som de Chronicles).

# New Tech Trees

## Horseman-line

The Horseman-line is available for:

1. Carthaginians -- no Raider
2. Choson -- no Raider
3. Greeks -- no Raider
4. Macedonians -- no Raider
5. Minoans
6. Persians
7. Yamato

## Spearman-line

The Spearman-line is available for every civ, but the **Elite Guardsman** upgrade is not available for the civilizations
below:

1. Carthaginians
2. Choson
3. Romans
4. Yamato

## Skirmisher-line

The Elite Skirmisher upgrade is not available only for the **Assyrians**.