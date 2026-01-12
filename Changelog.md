v0.1

# General Changes

## Units

### Archery Range

Bowman:
- Now costs 40 Food and 20 Gold, the same as the Improved Bowman and the Composite Bowman.
- TODO: revisar strings (precisa incluir upgrade).
- TODO: revisar strings de bowman-line e improved bowman-line.

Improved Bowman:
- Is now an upgrade to the Bowman.
- Has 5 base attack instead of 4.
- Hotkey for unit creation and unit upgrade adjusted.
- TODO: Revisar strings como upgrade em vez de base da linha.
- TODO: Revisar custo de upgrade.

Composite Bowman:
- Moved to the Iron Age (IV).
- Has 7 base attack instead of 5.
- Hotkey for unit creation and unit upgrade adjusted.
- TODO: Revisar custo de upgrade.

### Barracks

Slinger:
- No longer has a bonus damage against Archers.
- Gain a bonus damage against Infantry.
- TODO: ajustar os status para incluir o novo bônus
- TODO: ajustar menções em strings como counter de arqueiros.
- TODO: mencionar em strings como counter em todas as infantarias.

Elite Slinger (NEW):
- Upgrade to the Slinger avaliable at the Bronze Age (III).
- TODO: corrigir projétil --> criei e usei um novo projétil duplicando do Chronicles e ainda não funcionou. Reverti.
- TODO: ajustar os status

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
- TODO: ajustar status para que de fato seja melhor para explorar (mais visão em geral, revisar velocidade).

# TODOs em geral

- [ ]. Revisar parte lógica das Techtrees (effect).
- [ ]. Revisar parte visual das Techtrees (json).
- [x]. (Elite Slinger) Corrigir som de morte (está com o som de Chronicles).
- [ ]. Revisar status da Horseman-line.
- [ ]. Revisar bônus de civs e team bônus.
- [ ]. Conferir aplicação de bônus sobre unidades novas.
- [ ]. Verificar possibilidade de novos bônus para unidades novas.
- [ ]. Verificar possibilidade de aproveitar gráficos de ataque alternativos. Várias unidades têm os gráficos prontos,
       seria uma pena não utilizar, e dava para deixar mais diferenciadas as civilizações.

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

The Spearman-line is available for every civ, but **Elite Guardsman** is unavailable for the civs below:

1. Carthaginians
2. Choson
3. Romans
4. Yamato