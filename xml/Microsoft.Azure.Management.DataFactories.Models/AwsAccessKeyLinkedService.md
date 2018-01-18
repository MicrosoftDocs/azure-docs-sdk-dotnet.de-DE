<Type Name="AwsAccessKeyLinkedService" FullName="Microsoft.Azure.Management.DataFactories.Models.AwsAccessKeyLinkedService">
  <TypeSignature Language="C#" Value="public class AwsAccessKeyLinkedService : Microsoft.Azure.Management.DataFactories.Models.LinkedServiceTypeProperties" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit AwsAccessKeyLinkedService extends Microsoft.Azure.Management.DataFactories.Models.LinkedServiceTypeProperties" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.DataFactories.Models.AwsAccessKeyLinkedService" />
  <TypeSignature Language="VB.NET" Value="Public Class AwsAccessKeyLinkedService&#xA;Inherits LinkedServiceTypeProperties" />
  <TypeSignature Language="F#" Value="type AwsAccessKeyLinkedService = class&#xA;    inherit LinkedServiceTypeProperties" />
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
      <AttributeName>Microsoft.Azure.Management.DataFactories.Models.AdfTypeName("AwsAccessKey")</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            <span data-ttu-id="ef4ca-101">Ein Schlüsselbasierte Amazon Web Services (AWS) verknüpft Datenzugriffsdienst.</span><span class="sxs-lookup"><span data-stu-id="ef4ca-101">An access key-based Amazon Web Services (AWS) linked service.</span></span>
            <span data-ttu-id="ef4ca-102">Der Zugriffsschlüssel AWS Identity and Access Management (IAM) wird für alle AWS-Web-APIs verwendet.</span><span class="sxs-lookup"><span data-stu-id="ef4ca-102">The AWS Identity and Access Management (IAM) access key is used for all AWS web APIs.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public AwsAccessKeyLinkedService ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.Models.AwsAccessKeyLinkedService.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="ef4ca-103">Initialisiert eine neue Instanz der <see cref="T:Microsoft.Azure.Management.DataFactories.Models.AwsAccessKeyLinkedService" />-Klasse.</span><span class="sxs-lookup"><span data-stu-id="ef4ca-103">Initializes a new instance of the <see cref="T:Microsoft.Azure.Management.DataFactories.Models.AwsAccessKeyLinkedService" /> class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public AwsAccessKeyLinkedService (string accessKeyId, string secretAccessKey);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string accessKeyId, string secretAccessKey) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.Models.AwsAccessKeyLinkedService.#ctor(System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (accessKeyId As String, secretAccessKey As String)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.DataFactories.Models.AwsAccessKeyLinkedService : string * string -&gt; Microsoft.Azure.Management.DataFactories.Models.AwsAccessKeyLinkedService" Usage="new Microsoft.Azure.Management.DataFactories.Models.AwsAccessKeyLinkedService (accessKeyId, secretAccessKey)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="accessKeyId" Type="System.String" />
        <Parameter Name="secretAccessKey" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="accessKeyId">To be added.</param>
        <param name="secretAccessKey">To be added.</param>
        <summary>
            <span data-ttu-id="ef4ca-104">Initialisiert eine neue Instanz der dem <see cref="T:Microsoft.Azure.Management.DataFactories.Models.AwsAccessKeyLinkedService" /> Klasse mit erforderlichen Argumenten.</span><span class="sxs-lookup"><span data-stu-id="ef4ca-104">Initializes a new instance of the <see cref="T:Microsoft.Azure.Management.DataFactories.Models.AwsAccessKeyLinkedService" /> class with required arguments.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AccessKeyId">
      <MemberSignature Language="C#" Value="public string AccessKeyId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string AccessKeyId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactories.Models.AwsAccessKeyLinkedService.AccessKeyId" />
      <MemberSignature Language="VB.NET" Value="Public Property AccessKeyId As String" />
      <MemberSignature Language="F#" Value="member this.AccessKeyId : string with get, set" Usage="Microsoft.Azure.Management.DataFactories.Models.AwsAccessKeyLinkedService.AccessKeyId" />
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
            <span data-ttu-id="ef4ca-105">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="ef4ca-105">Required.</span></span> <span data-ttu-id="ef4ca-106">Der Zugriffsschlüssel IAM-ID.</span><span class="sxs-lookup"><span data-stu-id="ef4ca-106">The IAM access key ID.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SecretAccessKey">
      <MemberSignature Language="C#" Value="public string SecretAccessKey { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string SecretAccessKey" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactories.Models.AwsAccessKeyLinkedService.SecretAccessKey" />
      <MemberSignature Language="VB.NET" Value="Public Property SecretAccessKey As String" />
      <MemberSignature Language="F#" Value="member this.SecretAccessKey : string with get, set" Usage="Microsoft.Azure.Management.DataFactories.Models.AwsAccessKeyLinkedService.SecretAccessKey" />
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
            <span data-ttu-id="ef4ca-107">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="ef4ca-107">Required.</span></span> <span data-ttu-id="ef4ca-108">Der geheime IAM-Zugriffsschlüssel.</span><span class="sxs-lookup"><span data-stu-id="ef4ca-108">The IAM secret access key.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>