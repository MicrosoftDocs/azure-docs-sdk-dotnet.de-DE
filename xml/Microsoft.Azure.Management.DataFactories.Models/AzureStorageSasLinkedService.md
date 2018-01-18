<Type Name="AzureStorageSasLinkedService" FullName="Microsoft.Azure.Management.DataFactories.Models.AzureStorageSasLinkedService">
  <TypeSignature Language="C#" Value="public class AzureStorageSasLinkedService : Microsoft.Azure.Management.DataFactories.Models.LinkedServiceTypeProperties" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit AzureStorageSasLinkedService extends Microsoft.Azure.Management.DataFactories.Models.LinkedServiceTypeProperties" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.DataFactories.Models.AzureStorageSasLinkedService" />
  <TypeSignature Language="VB.NET" Value="Public Class AzureStorageSasLinkedService&#xA;Inherits LinkedServiceTypeProperties" />
  <TypeSignature Language="F#" Value="type AzureStorageSasLinkedService = class&#xA;    inherit LinkedServiceTypeProperties" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
    <AssemblyVersion>4.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Management.DataFactories.Models.LinkedServiceTypeProperties</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>Microsoft.Azure.Management.DataFactories.Models.AdfTypeName("AzureStorageSas")</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            <span data-ttu-id="60f0d-101">Azure Storage Shared Access Signatures (SAS) URI verknüpften Dienst an.</span><span class="sxs-lookup"><span data-stu-id="60f0d-101">Azure Storage Shared Access Signatures (SAS) URI linked service.</span></span> <span data-ttu-id="60f0d-102">Dieses Typs für verknüpfte Dienste kann verwendet werden, eingeschränkten Zugriff auf ein Azure Storage-Ressource mit einem SAS-URI angeben.</span><span class="sxs-lookup"><span data-stu-id="60f0d-102">This linked service type can be used to provide restricted access to an Azure Storage resource using a SAS URI.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public AzureStorageSasLinkedService ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.Models.AzureStorageSasLinkedService.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="60f0d-103">Initialisiert eine neue Instanz der <see cref="T:Microsoft.Azure.Management.DataFactories.Models.AzureStorageSasLinkedService" />-Klasse.</span><span class="sxs-lookup"><span data-stu-id="60f0d-103">Initializes a new instance of the <see cref="T:Microsoft.Azure.Management.DataFactories.Models.AzureStorageSasLinkedService" /> class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public AzureStorageSasLinkedService (string sasUri);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string sasUri) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.Models.AzureStorageSasLinkedService.#ctor(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (sasUri As String)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.DataFactories.Models.AzureStorageSasLinkedService : string -&gt; Microsoft.Azure.Management.DataFactories.Models.AzureStorageSasLinkedService" Usage="new Microsoft.Azure.Management.DataFactories.Models.AzureStorageSasLinkedService sasUri" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="sasUri" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="sasUri">To be added.</param>
        <summary>
            <span data-ttu-id="60f0d-104">Initialisiert eine neue Instanz der dem <see cref="T:Microsoft.Azure.Management.DataFactories.Models.AzureStorageSasLinkedService" /> Klasse mit erforderlichen Argumenten.</span><span class="sxs-lookup"><span data-stu-id="60f0d-104">Initializes a new instance of the <see cref="T:Microsoft.Azure.Management.DataFactories.Models.AzureStorageSasLinkedService" /> class with required arguments.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SasUri">
      <MemberSignature Language="C#" Value="public string SasUri { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string SasUri" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactories.Models.AzureStorageSasLinkedService.SasUri" />
      <MemberSignature Language="VB.NET" Value="Public Property SasUri As String" />
      <MemberSignature Language="F#" Value="member this.SasUri : string with get, set" Usage="Microsoft.Azure.Management.DataFactories.Models.AzureStorageSasLinkedService.SasUri" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.Azure.Management.DataFactories.Models.AdfRequired</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="60f0d-105">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="60f0d-105">Required.</span></span> <span data-ttu-id="60f0d-106">SAS-URI des Azure-Speicherressource.</span><span class="sxs-lookup"><span data-stu-id="60f0d-106">SAS URI of the Azure Storage resource.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>