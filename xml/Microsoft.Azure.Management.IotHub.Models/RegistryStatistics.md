<Type Name="RegistryStatistics" FullName="Microsoft.Azure.Management.IotHub.Models.RegistryStatistics">
  <TypeSignature Language="C#" Value="public class RegistryStatistics" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit RegistryStatistics extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.IotHub.Models.RegistryStatistics" />
  <TypeSignature Language="VB.NET" Value="Public Class RegistryStatistics" />
  <TypeSignature Language="F#" Value="type RegistryStatistics = class" />
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
            <span data-ttu-id="4aea2-101">Identität Registrierung Statistiken.</span><span class="sxs-lookup"><span data-stu-id="4aea2-101">Identity registry statistics.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public RegistryStatistics ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.IotHub.Models.RegistryStatistics.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.IotHub</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="4aea2-102">Initialisiert eine neue Instanz der RegistryStatistics-Klasse.</span><span class="sxs-lookup"><span data-stu-id="4aea2-102">Initializes a new instance of the RegistryStatistics class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public RegistryStatistics (Nullable&lt;long&gt; totalDeviceCount = null, Nullable&lt;long&gt; enabledDeviceCount = null, Nullable&lt;long&gt; disabledDeviceCount = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(valuetype System.Nullable`1&lt;int64&gt; totalDeviceCount, valuetype System.Nullable`1&lt;int64&gt; enabledDeviceCount, valuetype System.Nullable`1&lt;int64&gt; disabledDeviceCount) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.IotHub.Models.RegistryStatistics.#ctor(System.Nullable{System.Int64},System.Nullable{System.Int64},System.Nullable{System.Int64})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional totalDeviceCount As Nullable(Of Long) = null, Optional enabledDeviceCount As Nullable(Of Long) = null, Optional disabledDeviceCount As Nullable(Of Long) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.IotHub.Models.RegistryStatistics : Nullable&lt;int64&gt; * Nullable&lt;int64&gt; * Nullable&lt;int64&gt; -&gt; Microsoft.Azure.Management.IotHub.Models.RegistryStatistics" Usage="new Microsoft.Azure.Management.IotHub.Models.RegistryStatistics (totalDeviceCount, enabledDeviceCount, disabledDeviceCount)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.IotHub</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="totalDeviceCount" Type="System.Nullable&lt;System.Int64&gt;" />
        <Parameter Name="enabledDeviceCount" Type="System.Nullable&lt;System.Int64&gt;" />
        <Parameter Name="disabledDeviceCount" Type="System.Nullable&lt;System.Int64&gt;" />
      </Parameters>
      <Docs>
        <param name="totalDeviceCount"><span data-ttu-id="4aea2-103">Die Gesamtanzahl der Geräte in die identitätsregistrierung.</span><span class="sxs-lookup"><span data-stu-id="4aea2-103">The total count of devices in the identity registry.</span></span></param>
        <param name="enabledDeviceCount"><span data-ttu-id="4aea2-104">Die Anzahl der aktivierten Geräte in die identitätsregistrierung.</span><span class="sxs-lookup"><span data-stu-id="4aea2-104">The count of enabled devices in the identity registry.</span></span></param>
        <param name="disabledDeviceCount"><span data-ttu-id="4aea2-105">Die Anzahl der deaktivierte Geräte in die identitätsregistrierung.</span><span class="sxs-lookup"><span data-stu-id="4aea2-105">The count of disabled devices in the identity registry.</span></span></param>
        <summary>
            <span data-ttu-id="4aea2-106">Initialisiert eine neue Instanz der RegistryStatistics-Klasse.</span><span class="sxs-lookup"><span data-stu-id="4aea2-106">Initializes a new instance of the RegistryStatistics class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DisabledDeviceCount">
      <MemberSignature Language="C#" Value="public Nullable&lt;long&gt; DisabledDeviceCount { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int64&gt; DisabledDeviceCount" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.IotHub.Models.RegistryStatistics.DisabledDeviceCount" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property DisabledDeviceCount As Nullable(Of Long)" />
      <MemberSignature Language="F#" Value="member this.DisabledDeviceCount : Nullable&lt;int64&gt;" Usage="Microsoft.Azure.Management.IotHub.Models.RegistryStatistics.DisabledDeviceCount" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.IotHub</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="disabledDeviceCount")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int64&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="4aea2-107">Ruft die Anzahl der deaktivierte Geräte in die identitätsregistrierung.</span><span class="sxs-lookup"><span data-stu-id="4aea2-107">Gets the count of disabled devices in the identity registry.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EnabledDeviceCount">
      <MemberSignature Language="C#" Value="public Nullable&lt;long&gt; EnabledDeviceCount { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int64&gt; EnabledDeviceCount" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.IotHub.Models.RegistryStatistics.EnabledDeviceCount" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property EnabledDeviceCount As Nullable(Of Long)" />
      <MemberSignature Language="F#" Value="member this.EnabledDeviceCount : Nullable&lt;int64&gt;" Usage="Microsoft.Azure.Management.IotHub.Models.RegistryStatistics.EnabledDeviceCount" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.IotHub</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="enabledDeviceCount")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int64&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="4aea2-108">Ruft die Anzahl der aktivierten Geräte in die identitätsregistrierung.</span><span class="sxs-lookup"><span data-stu-id="4aea2-108">Gets the count of enabled devices in the identity registry.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TotalDeviceCount">
      <MemberSignature Language="C#" Value="public Nullable&lt;long&gt; TotalDeviceCount { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int64&gt; TotalDeviceCount" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.IotHub.Models.RegistryStatistics.TotalDeviceCount" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property TotalDeviceCount As Nullable(Of Long)" />
      <MemberSignature Language="F#" Value="member this.TotalDeviceCount : Nullable&lt;int64&gt;" Usage="Microsoft.Azure.Management.IotHub.Models.RegistryStatistics.TotalDeviceCount" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.IotHub</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="totalDeviceCount")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int64&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="4aea2-109">Ruft die Gesamtanzahl der Geräte in die identitätsregistrierung.</span><span class="sxs-lookup"><span data-stu-id="4aea2-109">Gets the total count of devices in the identity registry.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>