## API Report File for "@fluentui/react-label"

> Do not edit this file. It is a report generated by [API Extractor](https://api-extractor.com/).

```ts

import { ComponentPropsCompat } from '@fluentui/react-utilities';
import { ComponentStateCompat } from '@fluentui/react-utilities';
import { ObjectShorthandPropsCompat } from '@fluentui/react-utilities';
import * as React_2 from 'react';
import { ShorthandPropsCompat } from '@fluentui/react-utilities';

// @public
export const Label: React_2.ForwardRefExoticComponent<LabelProps & React_2.RefAttributes<HTMLElement>>;

// @public
export type LabelDefaultedProps = 'size';

// @public
export interface LabelProps extends ComponentPropsCompat, React_2.LabelHTMLAttributes<HTMLLabelElement> {
    disabled?: boolean;
    required?: boolean | ShorthandPropsCompat<ComponentPropsCompat>;
    size?: 'small' | 'medium' | 'large';
    strong?: boolean;
}

// @public
export type LabelShorthandProps = 'required';

// @public
export const labelShorthandProps: LabelShorthandProps[];

// @public
export interface LabelState extends ComponentStateCompat<LabelProps, LabelShorthandProps, LabelDefaultedProps> {
    ref: React_2.Ref<HTMLElement>;
    required?: ObjectShorthandPropsCompat<ComponentPropsCompat>;
}

// @public
export const renderLabel: (state: LabelState) => JSX.Element;

// @public
export const useLabel: (props: LabelProps, ref: React_2.Ref<HTMLElement>, defaultProps?: LabelProps | undefined) => LabelState;

// @public
export const useLabelStyles: (state: LabelState) => LabelState;


// (No @packageDocumentation comment for this package)

```