# SmartDate [![English](https://img.shields.io/badge/Language-English-blue.svg)](README.md) [![中文](https://img.shields.io/badge/Language-中文-red.svg)](README.zh-CN.md) [![한국어](https://img.shields.io/badge/Language-한국어-red.svg)](README.ko.md)

처음부터 새롭게 구상한 WPF용 현대적이고 사용자 정의 가능한 DatePicker 컨트롤

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![.NET](https://img.shields.io/badge/.NET-8.0-blue.svg)](https://dotnet.microsoft.com/download)
[![Stars](https://img.shields.io/github/stars/vickyqu115/smartdate.svg)](https://github.com/vickyqu115/smartdate/stargazers)
[![Issues](https://img.shields.io/github/issues/vickyqu115/smartdate.svg)](https://github.com/vickyqu115/smartdate/issues)

## 프로젝트 개요

SmartDate는 전통적인 DatePicker를 새롭게 구상한 사용자 정의 WPF 컨트롤입니다. 기본 제공되는 DatePicker를 상속받는 대신 Control 클래스부터 처음부터 구축하여, 현대적이고 유연하며 쉽게 사용자 정의할 수 있는 대안을 제공합니다. 이 프로젝트는 고급 WPF 기술과 컨트롤 개발 사례를 보여줍니다.

<img src="https://github.com/vickyqu115/smartdate/assets/52397976/b848c8ef-b8ad-4925-bae0-f8ab142bf69a" width="49%"/>
<img src="https://github.com/user-attachments/assets/aef43667-102d-4889-afd4-bb318da43e83" width="49%"/>

## 주요 기능 및 구현 사항
#### 1. 기초부터 시작한 사용자 정의 컨트롤 개발
- [x] 표준 DatePicker의 복잡성을 우회하여 Control 클래스 기반으로 구축
- [x] 날짜 선택 기능의 효율적인 구현
- [x] 현재 UI/UX 트렌드에 맞춘 현대적인 디자인

#### 2. 고급 WPF 기술
- [x] 중요 요소에 PART_ 명명 규칙 사용
- [x] 달력 레이아웃을 위한 UniformGrid가 적용된 사용자 정의 ListBox (CalendarBox)
- [x] 드롭다운 달력 표시를 위한 Popup 컨트롤

#### 3. Primitives 및 사용자 정의 컨트롤 통합
- [x] 달력 활성화를 위한 사용자 정의 ToggleButton (CalendarSwitch)
- [x] 월 이동을 위한 ChevronButton
- [x] 요일 표시를 위한 DayOfWeek 컨트롤

#### 4. 정교한 날짜 처리
- [x] 효율적인 달력 생성 알고리즘
- [x] 원활한 월 이동 및 날짜 선택

#### 5. MVVM 친화적 설계
- [x] 쉬운 데이터 바인딩을 위한 DependencyProperties (SelectedDate, CurrentMonth)
- [x] 사용자 상호작용을 위한 이벤트 기반 아키텍처

## 기술 심층 분석
- **사용자 정의 컨트롤 아키텍처**: DatePicker 상속의 복잡성을 피하고 Control 클래스에서 복잡한 컨트롤을 구축하는 방법을 보여줍니다.
- **PART_ 컨트롤 상호작용**: WPF의 핵심 패턴인 코드 비하인드 상호작용을 위한 PART_ 명명 요소 사용을 보여줍니다.
- **ListBox 사용자 정의**: UniformGrid를 사용한 수정된 ListBox로 사용자 정의 달력을 구현하여 고급 ItemsPanel 사용자 정의를 보여줍니다.
- **Popup 관리**: 드롭다운 기능을 위한 Popup 컨트롤의 효율적인 처리를 보여줍니다.
- **날짜 로직**: 정교한 날짜 계산 및 달력 생성 알고리즘을 구현합니다.

## 기술 스택
- WPF (Windows Presentation Foundation)
- .NET 8.0
- C# 10.0
- XAML

## 시작하기
### 필요 조건
- Visual Studio 2022 이상
- .NET 8.0 SDK

### 설치 및 실행
#### 1. 리포지토리 복제:

```
git clone https://github.com/vickyqu115/smartdate.git
```

#### 2. 솔루션 열기
- [x] Visual Studio
- [x] Visual Studio Code
- [x] JetBrains Rider

<img src="https://github.com/user-attachments/assets/af70f422-7057-4e77-a54d-042ee8358d2a" width="32%"/>
<img src="https://github.com/user-attachments/assets/e4feaa10-a107-4b58-8d13-1d8be620ec62" width="32%"/>
<img src="https://github.com/user-attachments/assets/5ff487f6-55e4-43e1-9abf-f8d419ee6943" width="32%"/>

#### 3. 빌드 및 실행
- [x] SmartDateApp을 시작 프로젝트로 설정
- [x] F5를 누르거나 실행 버튼 클릭
- [x] Windows 11 권장

## 학습 자료
- [구현에 대한 상세 아티클 (jamesnet.dev)](https://jamesnet.dev/article/43)
- [YouTube 튜토리얼 (영어)](https://bit.ly/4c8uGr3)
- [BiliBili 튜토리얼 (중국어)](https://bit.ly/3xOeyMJ)
- [CodeProject 아티클](https://bit.ly/4du4hVD)

## 기여하기
SmartDate에 대한 기여를 환영합니다! 이슈를 제출하거나, 풀 리퀘스트를 생성하거나, 개선 사항을 제안해 주세요.

## 라이선스
이 프로젝트는 MIT 라이선스 하에 배포됩니다. 자세한 내용은 [LICENSE](LICENSE) 파일을 참조하세요.

## 연락처
- 웹사이트: https://jamesnet.dev
- 이메일: vickyqu115@hotmail.com, james@jamesnet.dev

SmartDate로 고급 WPF 컨트롤 개발 기술을 탐험해보세요!

----

## Recognizing the Issues with the WPF DatePicker
The WPF DatePicker is one of the core controls in WPF, with a history spanning nearly 20 years. Compared to simpler controls like Buttons, TextBoxes, or CheckBoxes, the DatePicker has a more complex structure and stages, composed of multiple controls. This complexity necessitates high expertise for customization, making it difficult to use or modify the provided outdated controls.

## Understanding the WPF DatePicker
Analyzing and understanding the structure of the DatePicker and the interaction of its internal elements within the Template is extremely beneficial for enhancing fundamental design and analysis skills in WPF. This applies to all WPF controls, not just the DatePicker. However, since the DatePicker was designed according to outdated trends, it might be more efficient to implement a new CustomControl based on the basic Control.

## Source Code Download and Setup
This article identifies issues with using the basic DatePicker and demonstrates how to redesign it using a CustomControl approach. It is also beneficial to download the source code via GitHub to check the results firsthand and read along with this article.

First, download the source code using the following git command:
```
git clone https://github.com/vickyqu115/smartdate
```

Next, to run the solution file from the source code, you need an environment with Windows 10 or higher, Visual Studio 2022 or Rider, and .NET 8.0.

_SmartDate.sln_

<img src="https://jamesnetdev.blob.core.windows.net/articleimages/50f4296f-2792-4bdd-9af6-1cffd2f9f8f6.png" style="width: 300px"/>

## Project Structure
SmartDate consists of two projects:
- SmartDateControl
- SmartDateApp

SmartDateControl is a CustomControl Library that includes the SmartDate class along with all other subordinate CustomControl classes. SmartDateApp is a simple application project that guides users on how to use this control.

## Declaring and Using SmartDate
The usage is straightforward. Declare the namespace with xmlns and use SmartDate just like the standard DatePicker.

```xml
<Window x:Class="SmartDateApp.MainWindow"
        xmlns="http://schemas.microsoft.com/winfx/2006/xaml/presentation"
        xmlns:x="http://schemas.microsoft.com/winfx/2006/xaml"
        xmlns:d="http://schemas.microsoft.com/expression/blend/2008"
        xmlns:mc="http://schemas.openxmlformats.org/markup-compatibility/2006"
        xmlns:smart="clr-namespace:SmartDateControl.UI.Units;assembly=SmartDateControl"
        xmlns:theme="https://jamesnet.dev/xaml/presentation/themeswitch"
        mc:Ignorable="d"
        x:Name="Window"
        Title="SmartDate" Height="450" Width="800" Background="#FFFFFF">
    <Viewbox Width="500">
        <UniformGrid Margin="20" Columns="1" VerticalAlignment="Top">
            <smart:SmartDate SelectedDate="{Binding Created}"/>
            <DatePicker SelectedDate="{Binding Created}"/>
        </UniformGrid>
    </Viewbox>
</Window>
```

SelectedDate is a DependencyProperty and uses the same DateTime? type as DatePicker’s SelectedDate.

_Execution Results_

<img src="https://jamesnetdev.blob.core.windows.net/articleimages/fbfa4cd0-4b3b-426e-b894-b20473096e33.png" style="width: 300px; "/>

## Definition and Utilization of CustomControl
I have previously discussed the technology behind CustomControls in detail through four articles on CodeProject. If you need to understand and master CustomControls, please refer to these articles. Particularly, the article on RiotSlider delves deeply into the architecture of WPF CustomControls, so if you haven’t read it yet, I strongly recommend doing so.

Returning to the main discussion, let’s define CustomControl. Typically, a CustomControl targets classes derived from Control, but in reality, it includes all classes derived from DependencyObject, not just those inheriting Control, such as Panels, up to Visuals like Animations. However, as mentioned earlier, it only makes sense to implement CustomControls in layers that can utilize Templates, or at least DataContext. Therefore, implementing classes derived from FrameworkElement in the CustomControl style is seen as wise.

## Designing a New DatePicker: SmartDate
This article will detail how to implement a new CustomControl called SmartDate, derived from the most basic class, Control, without using the existing DatePicker.

## Choosing Control Over ContentControl
First, let’s examine the differences between ContentControl and Control. ContentControl offers not just the basic Template but also properties for Content and ContentTemplate. These properties are automatically linked through the ContentPresenter, setting up the relationship between ContentPresenter, Content, and ContentTemplate automatically. Consequently, choosing a derived control based on the basic usage of DataTemplate is advisable.

Is DatePicker fundamentally a control that utilizes DataTemplate? While opinions may vary, a complex control like DatePicker typically requires multiple DataTemplates and does not resemble a standard ContentControl. Indeed, DatePicker is derived from Control, and similar types of controls usually inherit from Control. For example, ComboBox might look similar to DatePicker but is an ItemsControl with an ItemsSource property.

Therefore, it is appropriate to base the implementation of SmartDate on Control, especially since SmartDate does not provide its own DataTemplate.

## Utilizing DataTemplate
Though SmartDate does not provide a DataTemplate by default, there are many points within various areas of the control where extending through DataTemplate could be beneficial.

For example, you can extend the ContentPresenter of the DayOfWeek control to add specific date processing, a common requirement among clients. This allows for various extensions such as triggers or converters for special dates.

By extending the SelectedDate binding area to a ContentPresenter, you can flexibly use it for selecting dates, incorporating formats ranging from a simple TextBlock to an editable TextBox or even including time.

## Negative Views on DataTemplate
DataTemplate fundamentally maintains versatility even in complex situations and is an essential template area for customization. However, whether to apply this versatility to specific controls like date pickers should be carefully considered. Using a DataTemplate means that all related logic must be separated into interactively implementable components. While this may seem practical, it is crucial to make sound judgments.

## Key Binding Properties of SmartDate (DependencyProperty)
This control includes a binding property named SelectedDate of type DateTime?. Since the default value might be null, it is declared as a nullable type, used for setting the date value selected through the calendar.

## SmartDate Template Design

The essential components that must be included in the ControlTemplate design are as follows:

- Popup
- ListBox
- ToggleButton

The Popup acts as a panel to contain the ListBox, which is the calendar, and the ListBox uses an internal ItemsPanel to implement the calendar with a UniformGrid. The ToggleButton is used as the calendar icon, and toggling the button changes the IsOpen property of the Popup to control the calendar window. This setup is similar in the basic DatePicker control as well, making it very beneficial to compare it with the actual open-source code of DatePicker.

Let’s now examine how the SmartDate control is structured in its Template.

_SmartDate: ControlTemplate_

```xml
<ControlTemplate TargetType="{x:Type units:SmartDate}">
    <Border Background="{TemplateBinding Background}"
            BorderBrush="{TemplateBinding BorderBrush}"
            BorderThickness="{TemplateBinding BorderThickness}" CornerRadius="4">
        <Grid>
            <units:CalendarSwitch x:Name="PART_Switch"/>
            <Popup x:Name="PART_Popup" StaysOpen="False" ...>
                <Border Background="{TemplateBinding Background}" ...>
                    <james:JamesGrid Rows="Auto,Auto,Auto" Columns="*">
                        <james:JamesGrid Rows="*" Columns="Auto,*,Auto">
                            <units:ChevronButton x:Name="PART_Left" Tag="Left"/>
                            <TextBlock Style="{StaticResource MonthStyle}"/>
                            <units:ChevronButton x:Name="PART_Right" Tag="Right"/>
                        </james:JamesGrid>
                        <UniformGrid Columns="7">
                            <units:DayOfWeek Grid.Column="0" Content="Su"/>
                            <units:DayOfWeek Grid.Column="1" Content="Mo"/>
                            <units:DayOfWeek Grid.Column="2" Content="Tu"/>
                            <units:DayOfWeek Grid.Column="3" Content="We"/>
                            <units:DayOfWeek Grid.Column="4" Content="Th"/>
                            <units:DayOfWeek Grid.Column="5" Content="Fr"/>
                            <units:DayOfWeek Grid.Column="6" Content="Sa"/>
                        </UniformGrid>
                        <units:CalendarBox x:Name="PART_ListBox"/>
                    </james:JamesGrid>
                </Border>
            </Popup>
        </Grid>
    </Border>
</ControlTemplate>
```

As you can see in the ControlTemplate, all previously mentioned components are included. The Popup is used as a basic control, and the CalendarSwitch is a calendar switching button that inherits from ToggleButton. Lastly, the CalendarBox, which inherits from ListBox, is used as the list control for selecting dates on the calendar.

Moreover, other components included are buttons to navigate to the previous and next months, a TextBlock to display the current month, and design elements to display the days of the week.

## CustomControl Not Intended for Reuse but for Internal Use Only
The SmartDate control is not only used by itself but also employs CustomControls within its Template. Not all CustomControls are intended for universal control implementation. In cases like SmartDate, they are implemented for specific purposes, which is a common practice from the perspective of WPF architecture.

Such types of controls are often categorized under the namespace 'Primitives.' This category includes controls like ToggleButton, Thumb, and ScrollBar, which are typically used not directly but within the internals of other controls.

Based on these architectural facts about WPF, it can be seen that the structure of the SmartDate control's Template does not significantly differ from the basic patterns of WPF.

## Understanding PART_ Control Items and Their Roles
The CustomControl structure does not automatically connect code and XAML like UserControls do. Thus, all interactions between the two are exclusively managed by _PART controls.

The predefined _PART controls include:
- PART_Switch
- PART_ListBox
- PART_Left
- PART_Right

These are assigned during the override of the SmartDate class's OnApplyTemplate method, where all necessary processes such as button events and date generation are implemented. It's a good practice to name controls with the PART_ prefix when passed through OnApplyTemplate. Moreover, naming these elements in XAML in a way that allows developers to anticipate what processes occur within the class based on the PART_ name would be exemplary.

## SmartDate.cs Source Code
Next, we will examine the core implementation contained within the SmartDate.cs class file. Key areas to focus on include:
- Declared DependencyProperty
- Definition of PART_ elements via OnApplyTemplate
- Date selection control logic through the SelectedDate property
- Utilization of SelectedItem/SelectedValue in CalendarBox

 _SmartDate: CustomControl_

```csharp
﻿using System;
using System.Collections.Generic;
using System.Linq;
using System.Text;
using System.Threading.Tasks;
using System.Windows;
using System.Windows.Controls;
using System.Windows.Controls.Primitives;
using System.Windows.Data;
using System.Windows.Documents;
using System.Windows.Input;
using System.Windows.Media;
using System.Windows.Media.Imaging;
using System.Windows.Navigation;
using System.Windows.Shapes;

namespace SmartDateControl.UI.Units
{
    public class SmartDate : Control
    {
        private Popup _popup;
        private CalendarSwitch _switch;
        private CalendarBox _listbox;

        public bool KeepPopupOpen
        {
            get { return (bool)GetValue(KeepPopupOpenProperty); }
            set { SetValue(KeepPopupOpenProperty, value); }
        }

        public static readonly DependencyProperty KeepPopupOpenProperty =
            DependencyProperty.Register("KeepPopupOpen", typeof(bool), typeof(SmartDate), new PropertyMetadata(true));



        public DateTime CurrentMonth
        {
            get { return (DateTime)GetValue(CurrentMonthProperty); }
            set { SetValue(CurrentMonthProperty, value); }
        }

        public static readonly DependencyProperty CurrentMonthProperty =
            DependencyProperty.Register("CurrentMonth", typeof(DateTime), typeof(SmartDate), new PropertyMetadata(null));



        public DateTime? SelectedDate
        {
            get { return (DateTime?)GetValue(SelectedDateProperty); }
            set { SetValue(SelectedDateProperty, value); }
        }

        public static readonly DependencyProperty SelectedDateProperty =
            DependencyProperty.Register("SelectedDate", typeof(DateTime?), typeof(SmartDate), new PropertyMetadata(null));



        static SmartDate()
        {
            DefaultStyleKeyProperty.OverrideMetadata(typeof(SmartDate), new FrameworkPropertyMetadata(typeof(SmartDate)));
        }
        public override void OnApplyTemplate()
        {
            base.OnApplyTemplate();

            _popup = (Popup)GetTemplateChild("PART_Popup");
            _switch = (CalendarSwitch)GetTemplateChild("PART_Switch");
            _listbox = (CalendarBox)GetTemplateChild("PART_ListBox");
            ChevronButton leftButton = (ChevronButton)GetTemplateChild("PART_Left");
            ChevronButton rightButton = (ChevronButton)GetTemplateChild("PART_Right");

            _popup.Closed += _popup_Closed;
            _switch.Click += _switch_Click;
            _listbox.MouseLeftButtonUp += _listbox_MouseLeftButtonUp;

            leftButton.Click += (s, e) => MoveMonthClick(-1);
            rightButton.Click += (s, e) => MoveMonthClick(1);

        }

        private void MoveMonthClick(int month)
        {
            GenerateCalendar(CurrentMonth.AddMonths(month));
        }

        private void _popup_Closed(object sender, EventArgs e)
        {
            _switch.IsChecked = IsMouseOver;
        }

        private void _switch_Click(object sender, RoutedEventArgs e)
        {
            if (_switch.IsChecked == true)
            {
                _popup.IsOpen = true;

                GenerateCalendar(SelectedDate ?? DateTime.Now);
            }
        }

        private void _listbox_MouseLeftButtonUp(object sender, MouseButtonEventArgs e)
        {
            if (_listbox.SelectedItem is CalendarBoxItem selected)
            {
                SelectedDate = selected.Date;
                GenerateCalendar(selected.Date);

                _popup.IsOpen = KeepPopupOpen; 
            }
        }
        private void GenerateCalendar(DateTime current)
        {
            if (current.ToString("yyyyMM") == CurrentMonth.ToString("yyyyMM")) return;

            CurrentMonth = current;
            _listbox.Items.Clear();
            DateTime fDayOfMonth = new(current.Year,current.Month,1);
            DateTime lDayOfMonth = fDayOfMonth.AddMonths(1).AddDays(-1);

            int fOffset = (int)fDayOfMonth.DayOfWeek;
            int lOffset = 6 - (int)lDayOfMonth.DayOfWeek;

            DateTime fDay = fDayOfMonth.AddDays(-fOffset);
            DateTime lDay = lDayOfMonth.AddDays(lOffset);

            for (DateTime day = fDay; day <= lDay; day = day.AddDays(1))
            {
                CalendarBoxItem boxItem = new();
                boxItem.Date = day;
                boxItem.DateFormat = day.ToString("yyyyMMdd");
                boxItem.Content = day.Day;
                boxItem.IsCurrentMonth = day.Month == current.Month;

                _listbox.Items.Add(boxItem);
            }
            if (SelectedDate != null)
            {
                _listbox.SelectedValue = SelectedDate.Value.ToString("yyyyMMdd");
            }
        }
    }
}
```

Firstly, the DependencyProperty is scrutinized, including essential properties like SelectedDate, which maintains the selected date. The KeepPopupOpen property determines whether to keep the window open after a date selection, and the CurrentMonth property, a DateTime property unseen in standard DatePicker controls, retains the current month's position to facilitate navigation through calendar months.

The GenerateCalendar method incorporates logic to recreate the calendar based on the selected date. The Offset calculation part is noteworthy here. Current dates set the calendar display, and to include preview dates from the previous and next months, a simple but crucial calculation is required.

```csharp
DateTime fDayOfMonth = new(current.Year,current.Month,1);
DateTime lDayOfMonth = fDayOfMonth.AddMonths(1).AddDays(-1);

int fOffset = (int)fDayOfMonth.DayOfWeek;
int lOffset = 6 - (int)lDayOfMonth.DayOfWeek;

DateTime fDay = fDayOfMonth.AddDays(-fOffset);
DateTime lDay = lDayOfMonth.AddDays(lOffset);
```

In terms of event handling, the calendar selection event utilizes MouseLeftButtonUp to align with typical button click behaviors. It’s apt because SelectionChanged events do not trigger if the selected value is chosen again, making it unsuitable in this context.

The interaction between the ToggleButton's IsChecked state, Popup's IsOpen, and Close functionalities are all implemented via events, providing a comprehensive interaction mechanism that is beneficial to learn through direct implementation.

## Additional Implementations
This application, crafted for tutorial purposes, allows for further functional expansions such as time selection or manual value adjustments. Implementing a calendar display tailored to specific customer requirements is also feasible within this framework.

## Introduction to SmartDate Implementation Tutorials and Source Code
The entire process of implementing the SmartDate control is available in tutorial videos on [YouTube](https://bit.ly/3xOeyMJ) and [Bilibili](https://bit.ly/3xI9DNh) and can be inspected on [GitHub](https://github.com/vickyqu115/smartdate). The videos, just over 50 minutes long, were developed over two months while balancing other professional duties, making them high-quality educational resources available for free. It's recommended to approach these tutorials with ample time and patience to ensure thorough learning.

Should you have any questions regarding WPF or related studies, feel free to engage in discussion. Our community is eager to assist in your exploration.
