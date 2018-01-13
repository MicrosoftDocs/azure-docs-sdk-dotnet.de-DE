<Type Name="LoadMetric" FullName="System.Fabric.LoadMetric">
  <TypeSignature Language="C#" Value="public sealed class LoadMetric" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi serializable sealed beforefieldinit LoadMetric extends System.Object" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.LoadMetric" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class LoadMetric" />
  <TypeSignature Language="F#" Value="type LoadMetric = class" />
  <AssemblyInfo>
    <AssemblyName>System.Fabric</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
      <para>Stellt den Namen der Metrik und den Runtime-Wert als Name / Wert-Paar, der Service Fabric gemeldet wird. Die Metrik lädt werden Service Fabric verwendet werden, um sicherzustellen, dass der Cluster gleichmäßig verwendet wird und ihre Kapazitäten für die Knoten nicht übersteigt angegebenen Metriken. <see cref="T:System.Fabric.LoadMetric" />Berichte werden bereitgestellt, um Service Fabric über <see cref="M:System.Fabric.IServicePartition.ReportLoad(System.Collections.Generic.IEnumerable{System.Fabric.LoadMetric})" />.</para>
    </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public LoadMetric (string name, int value);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string name, int32 value) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.LoadMetric.#ctor(System.String,System.Int32)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (name As String, value As Integer)" />
      <MemberSignature Language="F#" Value="new System.Fabric.LoadMetric : string * int -&gt; System.Fabric.LoadMetric" Usage="new System.Fabric.LoadMetric (name, value)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="value" Type="System.Int32" />
      </Parameters>
      <Docs>
        <param name="name">
          <para>Der Name der Metrik. Diese Zeichenfolge muss den Namen der die Metriken, die im angegebenen entsprechen den <see cref="P:System.Fabric.Description.ServiceDescription.Metrics" /> Sammlung, oder sie werden übergangen.</para>
        </param>
        <param name="value">
          <para>Der aktuelle Wert der Metrik als ganze Zahl.</para>
        </param>
        <summary>
          <para>Erstellt und initialisiert ein <see cref="T:System.Fabric.LoadMetric" /> Objekt mit dem angegebenen Namen und Last-Wert.</para>
        </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Name">
      <MemberSignature Language="C#" Value="public string Name { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Name" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.LoadMetric.Name" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Name As String" />
      <MemberSignature Language="F#" Value="member this.Name : string" Usage="System.Fabric.LoadMetric.Name" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>Gibt den Namen der Metrik, die der Dienst Bericht Pläne an. </para>
        </summary>
        <value>
          <para>Gibt <see cref="T:System.String" />zurück.</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Value">
      <MemberSignature Language="C#" Value="public int Value { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 Value" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.LoadMetric.Value" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Value As Integer" />
      <MemberSignature Language="F#" Value="member this.Value : int" Usage="System.Fabric.LoadMetric.Value" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>Gibt die aktuelle Auslastung der Metrik an.</para>
        </summary>
        <value>
          <para>Gibt <see cref="T:System.Int32" />zurück.</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>