## API Report File for "@vscode/webview-ui-toolkit"

> Do not edit this file. It is a report generated by [API Extractor](https://api-extractor.com/).

```ts

import { Anchor } from '@microsoft/fast-foundation';
import { AnchorOptions } from '@microsoft/fast-foundation';
import { Badge as Badge_2 } from '@microsoft/fast-foundation';
import { BaseProgress } from '@microsoft/fast-foundation';
import { Button as Button_2 } from '@microsoft/fast-foundation';
import { ButtonOptions } from '@microsoft/fast-foundation';
import { Checkbox as Checkbox_2 } from '@microsoft/fast-foundation';
import { CheckboxOptions } from '@microsoft/fast-foundation';
import type { Container } from '@microsoft/fast-foundation';
import { DataGrid as DataGrid_2 } from '@microsoft/fast-foundation';
import { DataGridCell as DataGridCell_2 } from '@microsoft/fast-foundation';
import { DataGridCellTypes } from '@microsoft/fast-foundation';
import { DataGridRow as DataGridRow_2 } from '@microsoft/fast-foundation';
import { DataGridRowTypes } from '@microsoft/fast-foundation';
import { DesignSystem } from '@microsoft/fast-foundation';
import { Divider as Divider_2 } from '@microsoft/fast-foundation';
import { DividerRole } from '@microsoft/fast-foundation';
import { SelectPosition as DropdownPosition } from '@microsoft/fast-foundation';
import { FoundationElementDefinition } from '@microsoft/fast-foundation';
import { FoundationElementRegistry } from '@microsoft/fast-foundation';
import { GenerateHeaderOptions } from '@microsoft/fast-foundation';
import { ListboxOption } from '@microsoft/fast-foundation';
import { ListboxOptionOptions } from '@microsoft/fast-foundation';
import { OverrideFoundationElementDefinition } from '@microsoft/fast-foundation';
import { ProgressRingOptions } from '@microsoft/fast-foundation';
import { Radio as Radio_2 } from '@microsoft/fast-foundation';
import { RadioGroup as RadioGroup_2 } from '@microsoft/fast-foundation';
import { Orientation as RadioGroupOrientation } from '@microsoft/fast-web-utilities';
import { RadioOptions } from '@microsoft/fast-foundation';
import { Select } from '@microsoft/fast-foundation';
import { SelectOptions } from '@microsoft/fast-foundation';
import { Tab } from '@microsoft/fast-foundation';
import { TabPanel } from '@microsoft/fast-foundation';
import { Tabs } from '@microsoft/fast-foundation';
import { TextArea as TextArea_2 } from '@microsoft/fast-foundation';
import { TextAreaResize } from '@microsoft/fast-foundation';
import { TextField as TextField_2 } from '@microsoft/fast-foundation';
import { TextFieldOptions } from '@microsoft/fast-foundation';
import { TextFieldType } from '@microsoft/fast-foundation';

// @public
export const allComponents: {
    vsCodeBadge: (overrideDefinition?: OverrideFoundationElementDefinition<FoundationElementDefinition> | undefined) => FoundationElementRegistry<FoundationElementDefinition, typeof Badge>;
    vsCodeButton: (overrideDefinition?: OverrideFoundationElementDefinition<ButtonOptions> | undefined) => FoundationElementRegistry<ButtonOptions, typeof Button>;
    vsCodeCheckbox: (overrideDefinition?: OverrideFoundationElementDefinition<CheckboxOptions> | undefined) => FoundationElementRegistry<CheckboxOptions, typeof Checkbox>;
    vsCodeDataGrid: (overrideDefinition?: OverrideFoundationElementDefinition<FoundationElementDefinition> | undefined) => FoundationElementRegistry<FoundationElementDefinition, typeof DataGrid>;
    vsCodeDataGridCell: (overrideDefinition?: OverrideFoundationElementDefinition<FoundationElementDefinition> | undefined) => FoundationElementRegistry<FoundationElementDefinition, typeof DataGridCell>;
    vsCodeDataGridRow: (overrideDefinition?: OverrideFoundationElementDefinition<FoundationElementDefinition> | undefined) => FoundationElementRegistry<FoundationElementDefinition, typeof DataGridRow>;
    vsCodeDivider: (overrideDefinition?: OverrideFoundationElementDefinition<FoundationElementDefinition> | undefined) => FoundationElementRegistry<FoundationElementDefinition, typeof Divider>;
    vsCodeDropdown: (overrideDefinition?: OverrideFoundationElementDefinition<SelectOptions> | undefined) => FoundationElementRegistry<SelectOptions, typeof Dropdown>;
    vsCodeLink: (overrideDefinition?: OverrideFoundationElementDefinition<AnchorOptions> | undefined) => FoundationElementRegistry<AnchorOptions, typeof Link>;
    vsCodeOption: (overrideDefinition?: OverrideFoundationElementDefinition<ListboxOptionOptions> | undefined) => FoundationElementRegistry<ListboxOptionOptions, typeof Option_2>;
    vsCodePanels: (overrideDefinition?: OverrideFoundationElementDefinition<FoundationElementDefinition> | undefined) => FoundationElementRegistry<FoundationElementDefinition, typeof Panels>;
    vsCodePanelTab: (overrideDefinition?: OverrideFoundationElementDefinition<FoundationElementDefinition> | undefined) => FoundationElementRegistry<FoundationElementDefinition, typeof PanelTab>;
    vsCodePanelView: (overrideDefinition?: OverrideFoundationElementDefinition<FoundationElementDefinition> | undefined) => FoundationElementRegistry<FoundationElementDefinition, typeof PanelView>;
    vsCodeProgressRing: (overrideDefinition?: OverrideFoundationElementDefinition<ProgressRingOptions> | undefined) => FoundationElementRegistry<ProgressRingOptions, typeof ProgressRing>;
    vsCodeRadioGroup: (overrideDefinition?: OverrideFoundationElementDefinition<FoundationElementDefinition> | undefined) => FoundationElementRegistry<FoundationElementDefinition, typeof RadioGroup>;
    vsCodeRadio: (overrideDefinition?: OverrideFoundationElementDefinition<RadioOptions> | undefined) => FoundationElementRegistry<RadioOptions, typeof Radio>;
    vsCodeTag: (overrideDefinition?: OverrideFoundationElementDefinition<FoundationElementDefinition> | undefined) => FoundationElementRegistry<FoundationElementDefinition, typeof Tag>;
    vsCodeTextArea: (overrideDefinition?: OverrideFoundationElementDefinition<FoundationElementDefinition> | undefined) => FoundationElementRegistry<FoundationElementDefinition, typeof TextArea>;
    vsCodeTextField: (overrideDefinition?: OverrideFoundationElementDefinition<TextFieldOptions> | undefined) => FoundationElementRegistry<TextFieldOptions, typeof TextField>;
    register(container?: Container, ...rest: any[]): void;
};

// @public
export class Badge extends Badge_2 {
    // @internal
    connectedCallback(): void;
}

// @public
export class Button extends Button_2 {
    appearance: ButtonAppearance;
    // @internal
    attributeChangedCallback(attrName: string, oldVal: string, newVal: string): void;
    // @internal
    connectedCallback(): void;
}

// @public
export type ButtonAppearance = 'primary' | 'secondary' | 'icon';

// @public
export class Checkbox extends Checkbox_2 {
    // @internal
    connectedCallback(): void;
}

// @public
export class DataGrid extends DataGrid_2 {
    // @internal
    connectedCallback(): void;
}

// @public
export class DataGridCell extends DataGridCell_2 {
}

export { DataGridCellTypes }

// @public
export class DataGridRow extends DataGridRow_2 {
}

export { DataGridRowTypes }

// @public
export class Divider extends Divider_2 {
}

export { DividerRole }

// @public
export class Dropdown extends Select {
}

// @public
export type DropdownOptions = SelectOptions;

export { DropdownPosition }

export { GenerateHeaderOptions }

// @public
export class Link extends Anchor {
}

// @public
export type LinkOptions = AnchorOptions;

// @public
class Option_2 extends ListboxOption {
    // @internal
    connectedCallback(): void;
}
export { Option_2 as Option }

// @public
export type OptionOptions = ListboxOptionOptions;

// @public
export class Panels extends Tabs {
    // @internal
    connectedCallback(): void;
}

// @public
export class PanelTab extends Tab {
    // @internal
    connectedCallback(): void;
}

// @public
export class PanelView extends TabPanel {
}

// @public
export class ProgressRing extends BaseProgress {
    // @internal
    attributeChangedCallback(attrName: string, oldVal: string, newVal: string): void;
    // @internal
    connectedCallback(): void;
}

// @public
export function provideVSCodeDesignSystem(element?: HTMLElement): DesignSystem;

// @public
export class Radio extends Radio_2 {
    // @internal
    connectedCallback(): void;
}

// @public
export class RadioGroup extends RadioGroup_2 {
    // @internal
    connectedCallback(): void;
}

export { RadioGroupOrientation }

// @public
export class Tag extends Badge_2 {
    // @internal
    connectedCallback(): void;
}

// @public
export class TextArea extends TextArea_2 {
    // @internal
    connectedCallback(): void;
}

export { TextAreaResize }

// @public
export class TextField extends TextField_2 {
    // @internal
    connectedCallback(): void;
}

export { TextFieldType }

// @public
export const vsCodeBadge: (overrideDefinition?: OverrideFoundationElementDefinition<FoundationElementDefinition> | undefined) => FoundationElementRegistry<FoundationElementDefinition, typeof Badge>;

// @public
export const vsCodeButton: (overrideDefinition?: OverrideFoundationElementDefinition<ButtonOptions> | undefined) => FoundationElementRegistry<ButtonOptions, typeof Button>;

// @public
export const vsCodeCheckbox: (overrideDefinition?: OverrideFoundationElementDefinition<CheckboxOptions> | undefined) => FoundationElementRegistry<CheckboxOptions, typeof Checkbox>;

// @public
export const vsCodeDataGrid: (overrideDefinition?: OverrideFoundationElementDefinition<FoundationElementDefinition> | undefined) => FoundationElementRegistry<FoundationElementDefinition, typeof DataGrid>;

// @public
export const vsCodeDataGridCell: (overrideDefinition?: OverrideFoundationElementDefinition<FoundationElementDefinition> | undefined) => FoundationElementRegistry<FoundationElementDefinition, typeof DataGridCell>;

// @public
export const vsCodeDataGridRow: (overrideDefinition?: OverrideFoundationElementDefinition<FoundationElementDefinition> | undefined) => FoundationElementRegistry<FoundationElementDefinition, typeof DataGridRow>;

// @public
export const vsCodeDivider: (overrideDefinition?: OverrideFoundationElementDefinition<FoundationElementDefinition> | undefined) => FoundationElementRegistry<FoundationElementDefinition, typeof Divider>;

// @public
export const vsCodeDropdown: (overrideDefinition?: OverrideFoundationElementDefinition<SelectOptions> | undefined) => FoundationElementRegistry<SelectOptions, typeof Dropdown>;

// @public
export const vsCodeLink: (overrideDefinition?: OverrideFoundationElementDefinition<AnchorOptions> | undefined) => FoundationElementRegistry<AnchorOptions, typeof Link>;

// @public
export const vsCodeOption: (overrideDefinition?: OverrideFoundationElementDefinition<ListboxOptionOptions> | undefined) => FoundationElementRegistry<ListboxOptionOptions, typeof Option_2>;

// @public
export const vsCodePanels: (overrideDefinition?: OverrideFoundationElementDefinition<FoundationElementDefinition> | undefined) => FoundationElementRegistry<FoundationElementDefinition, typeof Panels>;

// @public
export const vsCodePanelTab: (overrideDefinition?: OverrideFoundationElementDefinition<FoundationElementDefinition> | undefined) => FoundationElementRegistry<FoundationElementDefinition, typeof PanelTab>;

// @public
export const vsCodePanelView: (overrideDefinition?: OverrideFoundationElementDefinition<FoundationElementDefinition> | undefined) => FoundationElementRegistry<FoundationElementDefinition, typeof PanelView>;

// @public
export const vsCodeProgressRing: (overrideDefinition?: OverrideFoundationElementDefinition<ProgressRingOptions> | undefined) => FoundationElementRegistry<ProgressRingOptions, typeof ProgressRing>;

// @public
export const vsCodeRadio: (overrideDefinition?: OverrideFoundationElementDefinition<RadioOptions> | undefined) => FoundationElementRegistry<RadioOptions, typeof Radio>;

// @public
export const vsCodeRadioGroup: (overrideDefinition?: OverrideFoundationElementDefinition<FoundationElementDefinition> | undefined) => FoundationElementRegistry<FoundationElementDefinition, typeof RadioGroup>;

// @public
export const vsCodeTag: (overrideDefinition?: OverrideFoundationElementDefinition<FoundationElementDefinition> | undefined) => FoundationElementRegistry<FoundationElementDefinition, typeof Tag>;

// @public
export const vsCodeTextArea: (overrideDefinition?: OverrideFoundationElementDefinition<FoundationElementDefinition> | undefined) => FoundationElementRegistry<FoundationElementDefinition, typeof TextArea>;

// @public
export const vsCodeTextField: (overrideDefinition?: OverrideFoundationElementDefinition<TextFieldOptions> | undefined) => FoundationElementRegistry<TextFieldOptions, typeof TextField>;

// (No @packageDocumentation comment for this package)

```
