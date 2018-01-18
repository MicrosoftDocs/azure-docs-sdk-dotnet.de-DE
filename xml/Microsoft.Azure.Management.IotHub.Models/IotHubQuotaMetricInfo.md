<Type Name="IotHubQuotaMetricInfo" FullName="Microsoft.Azure.Management.IotHub.Models.IotHubQuotaMetricInfo">
  <TypeSignature Language="C#" Value="public class IotHubQuotaMetricInfo" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit IotHubQuotaMetricInfo extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.IotHub.Models.IotHubQuotaMetricInfo" />
  <TypeSignature Language="VB.NET" Value="Public Class IotHubQuotaMetricInfo" />
  <TypeSignature Language="F#" Value="type IotHubQuotaMetricInfo = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.IotHub</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="80a4e-101">Kontingent metrikeigenschaften.</span><span class="sxs-lookup"><span data-stu-id="80a4e-101">Quota metrics properties.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public IotHubQuotaMetricInfo ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.IotHub.Models.IotHubQuotaMetricInfo.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.IotHub</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="80a4e-102">Initialisiert eine neue Instanz der IotHubQuotaMetricInfo-Klasse.</span><span class="sxs-lookup"><span data-stu-id="80a4e-102">Initializes a new instance of the IotHubQuotaMetricInfo class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public IotHubQuotaMetricInfo (string name = null, Nullable&lt;long&gt; currentValue = null, Nullable&lt;long&gt; maxValue = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string name, valuetype System.Nullable`1&lt;int64&gt; currentValue, valuetype System.Nullable`1&lt;int64&gt; maxValue) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.IotHub.Models.IotHubQuotaMetricInfo.#ctor(System.String,System.Nullable{System.Int64},System.Nullable{System.Int64})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional name As String = null, Optional currentValue As Nullable(Of Long) = null, Optional maxValue As Nullable(Of Long) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.IotHub.Models.IotHubQuotaMetricInfo : string * Nullable&lt;int64&gt; * Nullable&lt;int64&gt; -&gt; Microsoft.Azure.Management.IotHub.Models.IotHubQuotaMetricInfo" Usage="new Microsoft.Azure.Management.IotHub.Models.IotHubQuotaMetricInfo (name, currentValue, maxValue)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.IotHub</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="currentValue" Type="System.Nullable&lt;System.Int64&gt;" />
        <Parameter Name="maxValue" Type="System.Nullable&lt;System.Int64&gt;" />
      </Parameters>
      <Docs>
        <param name="name"><span data-ttu-id="80a4e-103">Der Name der Metrik Kontingent.</span><span class="sxs-lookup"><span data-stu-id="80a4e-103">The name of the quota metric.</span></span></param>
        <param name="currentValue"><span data-ttu-id="80a4e-104">Der aktuelle Wert für die Metrik "Quota".</span><span class="sxs-lookup"><span data-stu-id="80a4e-104">The current value for the quota metric.</span></span></param>
        <param name="maxValue"><span data-ttu-id="80a4e-105">Der Maximalwert der Metrik Kontingent.</span><span class="sxs-lookup"><span data-stu-id="80a4e-105">The maximum value of the quota metric.</span></span></param>
        <summary>
            <span data-ttu-id="80a4e-106">Initialisiert eine neue Instanz der IotHubQuotaMetricInfo-Klasse.</span><span class="sxs-lookup"><span data-stu-id="80a4e-106">Initializes a new instance of the IotHubQuotaMetricInfo class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CurrentValue">
      <MemberSignature Language="C#" Value="public Nullable&lt;long&gt; CurrentValue { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int64&gt; CurrentValue" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.IotHub.Models.IotHubQuotaMetricInfo.CurrentValue" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property CurrentValue As Nullable(Of Long)" />
      <MemberSignature Language="F#" Value="member this.CurrentValue : Nullable&lt;int64&gt;" Usage="Microsoft.Azure.Management.IotHub.Models.IotHubQuotaMetricInfo.CurrentValue" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.IotHub</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="CurrentValue")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int64&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="80a4e-107">Ruft den aktuellen Wert für die Metrik "Quota".</span><span class="sxs-lookup"><span data-stu-id="80a4e-107">Gets the current value for the quota metric.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MaxValue">
      <MemberSignature Language="C#" Value="public Nullable&lt;long&gt; MaxValue { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int64&gt; MaxValue" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.IotHub.Models.IotHubQuotaMetricInfo.MaxValue" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property MaxValue As Nullable(Of Long)" />
      <MemberSignature Language="F#" Value="member this.MaxValue : Nullable&lt;int64&gt;" Usage="Microsoft.Azure.Management.IotHub.Models.IotHubQuotaMetricInfo.MaxValue" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.IotHub</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="MaxValue")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int64&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="80a4e-108">Ruft den Maximalwert der Metrik Kontingent ab.</span><span class="sxs-lookup"><span data-stu-id="80a4e-108">Gets the maximum value of the quota metric.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Name">
      <MemberSignature Language="C#" Value="public string Name { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Name" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.IotHub.Models.IotHubQuotaMetricInfo.Name" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Name As String" />
      <MemberSignature Language="F#" Value="member this.Name : string" Usage="Microsoft.Azure.Management.IotHub.Models.IotHubQuotaMetricInfo.Name" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.IotHub</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="Name")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="80a4e-109">Ruft den Namen der Metrik Kontingent ab.</span><span class="sxs-lookup"><span data-stu-id="80a4e-109">Gets the name of the quota metric.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>