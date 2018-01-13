<Type Name="Metric" FullName="Microsoft.ServiceBus.Management.Metric">
  <TypeSignature Language="C#" Value="public class Metric" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit Metric extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceBus.Management.Metric" />
  <TypeSignature Language="VB.NET" Value="Public Class Metric" />
  <TypeSignature Language="F#" Value="type Metric = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.ServiceBus</AssemblyName>
    <AssemblyVersion>3.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>Stellt die Metrik, die zum Überwachen des Status von Service Bus verwendet.</summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public Metric ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Management.Metric.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>To be added.</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DisplayName">
      <MemberSignature Language="C#" Value="public string DisplayName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string DisplayName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Management.Metric.DisplayName" />
      <MemberSignature Language="VB.NET" Value="Public Property DisplayName As String" />
      <MemberSignature Language="F#" Value="member this.DisplayName : string with get, set" Usage="Microsoft.ServiceBus.Management.Metric.DisplayName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>Ruft ab oder legt den Anzeigenamen der Metrik.</summary>
        <value>Der Anzeigename der Metrik.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Name">
      <MemberSignature Language="C#" Value="public string Name { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Name" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Management.Metric.Name" />
      <MemberSignature Language="VB.NET" Value="Public Property Name As String" />
      <MemberSignature Language="F#" Value="member this.Name : string with get, set" Usage="Microsoft.ServiceBus.Management.Metric.Name" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.ComponentModel.DataAnnotations.Key</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>Ruft ab oder legt den Namen der Metrik.</summary>
        <value>Der Name der Metrik.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PrimaryAggregation">
      <MemberSignature Language="C#" Value="public string PrimaryAggregation { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string PrimaryAggregation" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Management.Metric.PrimaryAggregation" />
      <MemberSignature Language="VB.NET" Value="Public Property PrimaryAggregation As String" />
      <MemberSignature Language="F#" Value="member this.PrimaryAggregation : string with get, set" Usage="Microsoft.ServiceBus.Management.Metric.PrimaryAggregation" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>Abrufen oder festlegen die primäre Aggregation für die Metrik.</summary>
        <value>Die primäre Aggregation für die Metrik.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Rollups">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.ICollection&lt;Microsoft.ServiceBus.Management.MetricRollup&gt; Rollups { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.ICollection`1&lt;class Microsoft.ServiceBus.Management.MetricRollup&gt; Rollups" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Management.Metric.Rollups" />
      <MemberSignature Language="VB.NET" Value="Public Property Rollups As ICollection(Of MetricRollup)" />
      <MemberSignature Language="F#" Value="member this.Rollups : System.Collections.Generic.ICollection&lt;Microsoft.ServiceBus.Management.MetricRollup&gt; with get, set" Usage="Microsoft.ServiceBus.Management.Metric.Rollups" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.ICollection&lt;Microsoft.ServiceBus.Management.MetricRollup&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>Ruft ab oder legt die Auflistung der Metrik Rollup.</summary>
        <value>Die Auflistung der Metrik Rollup.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Unit">
      <MemberSignature Language="C#" Value="public string Unit { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Unit" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Management.Metric.Unit" />
      <MemberSignature Language="VB.NET" Value="Public Property Unit As String" />
      <MemberSignature Language="F#" Value="member this.Unit : string with get, set" Usage="Microsoft.ServiceBus.Management.Metric.Unit" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>Ruft ab oder legt fest, Metrik.</summary>
        <value>Die Metrik Einheit.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>