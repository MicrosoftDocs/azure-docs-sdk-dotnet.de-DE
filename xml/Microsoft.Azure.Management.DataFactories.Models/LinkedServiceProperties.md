<Type Name="LinkedServiceProperties" FullName="Microsoft.Azure.Management.DataFactories.Models.LinkedServiceProperties">
  <TypeSignature Language="C#" Value="public class LinkedServiceProperties : Microsoft.Azure.Management.DataFactories.Models.AdfResourceProperties&lt;Microsoft.Azure.Management.DataFactories.Models.LinkedServiceTypeProperties,Microsoft.Azure.Management.DataFactories.Models.GenericLinkedService&gt;" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit LinkedServiceProperties extends Microsoft.Azure.Management.DataFactories.Models.AdfResourceProperties`2&lt;class Microsoft.Azure.Management.DataFactories.Models.LinkedServiceTypeProperties, class Microsoft.Azure.Management.DataFactories.Models.GenericLinkedService&gt;" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.DataFactories.Models.LinkedServiceProperties" />
  <TypeSignature Language="VB.NET" Value="Public Class LinkedServiceProperties&#xA;Inherits AdfResourceProperties(Of LinkedServiceTypeProperties, GenericLinkedService)" />
  <TypeSignature Language="F#" Value="type LinkedServiceProperties = class&#xA;    inherit AdfResourceProperties&lt;LinkedServiceTypeProperties, GenericLinkedService&gt;" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
    <AssemblyVersion>4.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Management.DataFactories.Models.AdfResourceProperties&lt;Microsoft.Azure.Management.DataFactories.Models.LinkedServiceTypeProperties,Microsoft.Azure.Management.DataFactories.Models.GenericLinkedService&gt;</BaseTypeName>
    <BaseTypeArguments>
      <BaseTypeArgument TypeParamName="TExtensibleTypeProperties">Microsoft.Azure.Management.DataFactories.Models.LinkedServiceTypeProperties</BaseTypeArgument>
      <BaseTypeArgument TypeParamName="TGenericTypeProperties">Microsoft.Azure.Management.DataFactories.Models.GenericLinkedService</BaseTypeArgument>
    </BaseTypeArguments>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="69f7b-101">Data Factory LinkedService-Eigenschaften.</span><span class="sxs-lookup"><span data-stu-id="69f7b-101">Data factory linkedService properties.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public LinkedServiceProperties (Microsoft.Azure.Management.DataFactories.Models.LinkedServiceTypeProperties typeProperties);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class Microsoft.Azure.Management.DataFactories.Models.LinkedServiceTypeProperties typeProperties) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.Models.LinkedServiceProperties.#ctor(Microsoft.Azure.Management.DataFactories.Models.LinkedServiceTypeProperties)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (typeProperties As LinkedServiceTypeProperties)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.DataFactories.Models.LinkedServiceProperties : Microsoft.Azure.Management.DataFactories.Models.LinkedServiceTypeProperties -&gt; Microsoft.Azure.Management.DataFactories.Models.LinkedServiceProperties" Usage="new Microsoft.Azure.Management.DataFactories.Models.LinkedServiceProperties typeProperties" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="typeProperties" Type="Microsoft.Azure.Management.DataFactories.Models.LinkedServiceTypeProperties" />
      </Parameters>
      <Docs>
        <param name="typeProperties">To be added.</param>
        <summary>To be added.</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public LinkedServiceProperties (Microsoft.Azure.Management.DataFactories.Models.GenericLinkedService typeProperties, string typeName);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class Microsoft.Azure.Management.DataFactories.Models.GenericLinkedService typeProperties, string typeName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.Models.LinkedServiceProperties.#ctor(Microsoft.Azure.Management.DataFactories.Models.GenericLinkedService,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (typeProperties As GenericLinkedService, typeName As String)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.DataFactories.Models.LinkedServiceProperties : Microsoft.Azure.Management.DataFactories.Models.GenericLinkedService * string -&gt; Microsoft.Azure.Management.DataFactories.Models.LinkedServiceProperties" Usage="new Microsoft.Azure.Management.DataFactories.Models.LinkedServiceProperties (typeProperties, typeName)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="typeProperties" Type="Microsoft.Azure.Management.DataFactories.Models.GenericLinkedService" />
        <Parameter Name="typeName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="typeProperties">To be added.</param>
        <param name="typeName">To be added.</param>
        <summary>To be added.</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Description">
      <MemberSignature Language="C#" Value="public string Description { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Description" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactories.Models.LinkedServiceProperties.Description" />
      <MemberSignature Language="VB.NET" Value="Public Property Description As String" />
      <MemberSignature Language="F#" Value="member this.Description : string with get, set" Usage="Microsoft.Azure.Management.DataFactories.Models.LinkedServiceProperties.Description" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="69f7b-102">Optional.</span><span class="sxs-lookup"><span data-stu-id="69f7b-102">Optional.</span></span> <span data-ttu-id="69f7b-103">Data Factory LinkedService-Beschreibung.</span><span class="sxs-lookup"><span data-stu-id="69f7b-103">Data factory linkedService description.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ErrorMessage">
      <MemberSignature Language="C#" Value="public string ErrorMessage { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ErrorMessage" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactories.Models.LinkedServiceProperties.ErrorMessage" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ErrorMessage As String" />
      <MemberSignature Language="F#" Value="member this.ErrorMessage : string" Usage="Microsoft.Azure.Management.DataFactories.Models.LinkedServiceProperties.ErrorMessage" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="69f7b-104">Optional.</span><span class="sxs-lookup"><span data-stu-id="69f7b-104">Optional.</span></span> <span data-ttu-id="69f7b-105">Fehler beim Verarbeiten der LinkedService-Anforderung.</span><span class="sxs-lookup"><span data-stu-id="69f7b-105">Error in processing linkedService request.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="HubName">
      <MemberSignature Language="C#" Value="public string HubName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string HubName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactories.Models.LinkedServiceProperties.HubName" />
      <MemberSignature Language="VB.NET" Value="Public Property HubName As String" />
      <MemberSignature Language="F#" Value="member this.HubName : string with get, set" Usage="Microsoft.Azure.Management.DataFactories.Models.LinkedServiceProperties.HubName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="69f7b-106">Optional.</span><span class="sxs-lookup"><span data-stu-id="69f7b-106">Optional.</span></span> <span data-ttu-id="69f7b-107">Der Name des Hubs, dass dieser verknüpfte Dienst gehört.</span><span class="sxs-lookup"><span data-stu-id="69f7b-107">The name of the Hub that this linked service belongs to.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ProvisioningState">
      <MemberSignature Language="C#" Value="public string ProvisioningState { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ProvisioningState" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactories.Models.LinkedServiceProperties.ProvisioningState" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ProvisioningState As String" />
      <MemberSignature Language="F#" Value="member this.ProvisioningState : string" Usage="Microsoft.Azure.Management.DataFactories.Models.LinkedServiceProperties.ProvisioningState" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="69f7b-108">Optional.</span><span class="sxs-lookup"><span data-stu-id="69f7b-108">Optional.</span></span> <span data-ttu-id="69f7b-109">Der Bereitstellungsstatus des verknüpften Diensts.</span><span class="sxs-lookup"><span data-stu-id="69f7b-109">The provisioning state of the linked service.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>