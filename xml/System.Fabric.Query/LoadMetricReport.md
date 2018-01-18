<Type Name="LoadMetricReport" FullName="System.Fabric.Query.LoadMetricReport">
  <TypeSignature Language="C#" Value="public sealed class LoadMetricReport" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit LoadMetricReport extends System.Object" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.Query.LoadMetricReport" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class LoadMetricReport" />
  <TypeSignature Language="F#" Value="type LoadMetricReport = class" />
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
      <para><span data-ttu-id="30cdb-101">Stellt den Metrikbericht laden.</span><span class="sxs-lookup"><span data-stu-id="30cdb-101">Represents the load metric report.</span></span></para>
    </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public LoadMetricReport ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Query.LoadMetricReport.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
          <para><span data-ttu-id="30cdb-102">Initialisiert eine neue Instanz der <see cref="T:System.Fabric.Query.LoadMetricReport" />-Klasse.</span><span class="sxs-lookup"><span data-stu-id="30cdb-102">Initializes a new instance of the <see cref="T:System.Fabric.Query.LoadMetricReport" /> class.</span></span></para>
        </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="LastReportedUtc">
      <MemberSignature Language="C#" Value="public DateTime LastReportedUtc { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.DateTime LastReportedUtc" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Query.LoadMetricReport.LastReportedUtc" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property LastReportedUtc As DateTime" />
      <MemberSignature Language="F#" Value="member this.LastReportedUtc : DateTime" Usage="System.Fabric.Query.LoadMetricReport.LastReportedUtc" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.DateTime</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para><span data-ttu-id="30cdb-103">Ruft die UTC-Zeit, wenn die Last gemeldet wird.</span><span class="sxs-lookup"><span data-stu-id="30cdb-103">Gets the UTC time when the load is reported.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="30cdb-104">Die UTC-Zeit, wenn die Last gemeldet wird.</span><span class="sxs-lookup"><span data-stu-id="30cdb-104">The UTC time when the load is reported.</span></span></para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Name">
      <MemberSignature Language="C#" Value="public string Name { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Name" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Query.LoadMetricReport.Name" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Name As String" />
      <MemberSignature Language="F#" Value="member this.Name : string" Usage="System.Fabric.Query.LoadMetricReport.Name" />
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
          <para><span data-ttu-id="30cdb-105">Ruft den Namen der Metrik.</span><span class="sxs-lookup"><span data-stu-id="30cdb-105">Gets the name of the metric.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="30cdb-106">Der Name der Metrik.</span><span class="sxs-lookup"><span data-stu-id="30cdb-106">The name of the metric.</span></span></para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Value">
      <MemberSignature Language="C#" Value="public int Value { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 Value" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Query.LoadMetricReport.Value" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Value As Integer" />
      <MemberSignature Language="F#" Value="member this.Value : int" Usage="System.Fabric.Query.LoadMetricReport.Value" />
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
          <para><span data-ttu-id="30cdb-107">Ruft den Wert des Ladevorgangs für die Metrik ab.</span><span class="sxs-lookup"><span data-stu-id="30cdb-107">Gets the value of the load for the metric.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="30cdb-108">Der Wert des Ladevorgangs für die Metrik.</span><span class="sxs-lookup"><span data-stu-id="30cdb-108">The value of the load for the metric.</span></span></para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>