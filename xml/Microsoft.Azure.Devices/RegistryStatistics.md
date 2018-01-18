<Type Name="RegistryStatistics" FullName="Microsoft.Azure.Devices.RegistryStatistics">
  <TypeSignature Language="C#" Value="public class RegistryStatistics" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit RegistryStatistics extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Devices.RegistryStatistics" />
  <TypeSignature Language="VB.NET" Value="Public Class RegistryStatistics" />
  <TypeSignature Language="F#" Value="type RegistryStatistics = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Devices</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="44c8f-101">Enthält Statistiken zur Registrierung Geräte, die aus IotHub abgerufen werden können.</span><span class="sxs-lookup"><span data-stu-id="44c8f-101">Contains device registry statistics that can be retrieved from IotHub.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public RegistryStatistics ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Devices.RegistryStatistics.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>To be added.</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DisabledDeviceCount">
      <MemberSignature Language="C#" Value="public long DisabledDeviceCount { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 DisabledDeviceCount" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Devices.RegistryStatistics.DisabledDeviceCount" />
      <MemberSignature Language="VB.NET" Value="Public Property DisabledDeviceCount As Long" />
      <MemberSignature Language="F#" Value="member this.DisabledDeviceCount : int64 with get, set" Usage="Microsoft.Azure.Devices.RegistryStatistics.DisabledDeviceCount" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="disabledDeviceCount")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Int64</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="44c8f-102">Ruft ab oder legt die Anzahl aller deaktivierten Geräte</span><span class="sxs-lookup"><span data-stu-id="44c8f-102">Gets or sets the count of all disabled Devices</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EnabledDeviceCount">
      <MemberSignature Language="C#" Value="public long EnabledDeviceCount { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 EnabledDeviceCount" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Devices.RegistryStatistics.EnabledDeviceCount" />
      <MemberSignature Language="VB.NET" Value="Public Property EnabledDeviceCount As Long" />
      <MemberSignature Language="F#" Value="member this.EnabledDeviceCount : int64 with get, set" Usage="Microsoft.Azure.Devices.RegistryStatistics.EnabledDeviceCount" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="enabledDeviceCount")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Int64</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="44c8f-103">Ruft ab oder legt die Anzahl aller aktivierten Geräte</span><span class="sxs-lookup"><span data-stu-id="44c8f-103">Gets or sets the count of all enabled Devices</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TotalDeviceCount">
      <MemberSignature Language="C#" Value="public long TotalDeviceCount { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 TotalDeviceCount" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Devices.RegistryStatistics.TotalDeviceCount" />
      <MemberSignature Language="VB.NET" Value="Public Property TotalDeviceCount As Long" />
      <MemberSignature Language="F#" Value="member this.TotalDeviceCount : int64 with get, set" Usage="Microsoft.Azure.Devices.RegistryStatistics.TotalDeviceCount" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="totalDeviceCount")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Int64</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="44c8f-104">Ruft ab oder legt die Anzahl aller Geräte</span><span class="sxs-lookup"><span data-stu-id="44c8f-104">Gets or sets the count of all Devices</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>