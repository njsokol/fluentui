## API Report File for "@fluentui/react-spinbutton"

> Do not edit this file. It is a report generated by [API Extractor](https://api-extractor.com/).

```ts

import type { ComponentProps } from '@fluentui/react-utilities';
import type { ComponentState } from '@fluentui/react-utilities';
import type { ForwardRefComponent } from '@fluentui/react-utilities';
import type { IntrinsicShorthandProps } from '@fluentui/react-utilities';
import * as React_2 from 'react';

// @public
export const renderSpinButton_unstable: (state: SpinButtonState) => JSX.Element;

// @public
export const SpinButton: ForwardRefComponent<SpinButtonProps>;

// @public (undocumented)
export const spinButtonClassName = "fui-SpinButton";

// @public (undocumented)
export type SpinButtonCommons = {};

// @public
export type SpinButtonProps = ComponentProps<SpinButtonSlots> & SpinButtonCommons;

// @public (undocumented)
export type SpinButtonSlots = {
    root: IntrinsicShorthandProps<'div'>;
};

// @public
export type SpinButtonState = ComponentState<SpinButtonSlots> & SpinButtonCommons;

// @public
export const useSpinButton_unstable: (props: SpinButtonProps, ref: React_2.Ref<HTMLElement>) => SpinButtonState;

// @public
export const useSpinButtonStyles_unstable: (state: SpinButtonState) => SpinButtonState;

// (No @packageDocumentation comment for this package)

```