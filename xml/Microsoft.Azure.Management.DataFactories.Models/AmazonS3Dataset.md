<Type Name="AmazonS3Dataset" FullName="Microsoft.Azure.Management.DataFactories.Models.AmazonS3Dataset">
  <TypeSignature Language="C#" Value="public class AmazonS3Dataset : Microsoft.Azure.Management.DataFactories.Models.DatasetTypeProperties" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit AmazonS3Dataset extends Microsoft.Azure.Management.DataFactories.Models.DatasetTypeProperties" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.DataFactories.Models.AmazonS3Dataset" />
  <TypeSignature Language="VB.NET" Value="Public Class AmazonS3Dataset&#xA;Inherits DatasetTypeProperties" />
  <TypeSignature Language="F#" Value="type AmazonS3Dataset = class&#xA;    inherit DatasetTypeProperties" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
    <AssemblyVersion>4.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Management.DataFactories.Models.DatasetTypeProperties</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>Microsoft.Azure.Management.DataFactories.Models.AdfTypeName("AmazonS3")</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            <span data-ttu-id="08489-101">Ein einzelnes Objekt für die einfache Amazon-Speicherdienst (S3) oder einen Satz von S3-Objekten.</span><span class="sxs-lookup"><span data-stu-id="08489-101">A single Amazon Simple Storage Service (S3) object or a set of S3 objects.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public AmazonS3Dataset ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.Models.AmazonS3Dataset.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="08489-102">Initialisiert eine neue Instanz der <see cref="T:Microsoft.Azure.Management.DataFactories.Models.AmazonS3Dataset" />-Klasse.</span><span class="sxs-lookup"><span data-stu-id="08489-102">Initializes a new instance of the <see cref="T:Microsoft.Azure.Management.DataFactories.Models.AmazonS3Dataset" /> class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public AmazonS3Dataset (string bucketName);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string bucketName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.Models.AmazonS3Dataset.#ctor(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (bucketName As String)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.DataFactories.Models.AmazonS3Dataset : string -&gt; Microsoft.Azure.Management.DataFactories.Models.AmazonS3Dataset" Usage="new Microsoft.Azure.Management.DataFactories.Models.AmazonS3Dataset bucketName" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="bucketName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="bucketName">To be added.</param>
        <summary>
            <span data-ttu-id="08489-103">Initialisiert eine neue Instanz der dem <see cref="T:Microsoft.Azure.Management.DataFactories.Models.AmazonS3Dataset" /> Klasse mit erforderlichen Argumenten.</span><span class="sxs-lookup"><span data-stu-id="08489-103">Initializes a new instance of the <see cref="T:Microsoft.Azure.Management.DataFactories.Models.AmazonS3Dataset" /> class with required arguments.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BucketName">
      <MemberSignature Language="C#" Value="public string BucketName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string BucketName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactories.Models.AmazonS3Dataset.BucketName" />
      <MemberSignature Language="VB.NET" Value="Public Property BucketName As String" />
      <MemberSignature Language="F#" Value="member this.BucketName : string with get, set" Usage="Microsoft.Azure.Management.DataFactories.Models.AmazonS3Dataset.BucketName" />
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
            <span data-ttu-id="08489-104">Der Name des Amazon-S3-Buckets.</span><span class="sxs-lookup"><span data-stu-id="08489-104">The name of the Amazon S3 bucket.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Compression">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.DataFactories.Models.Compression Compression { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.DataFactories.Models.Compression Compression" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactories.Models.AmazonS3Dataset.Compression" />
      <MemberSignature Language="VB.NET" Value="Public Property Compression As Compression" />
      <MemberSignature Language="F#" Value="member this.Compression : Microsoft.Azure.Management.DataFactories.Models.Compression with get, set" Usage="Microsoft.Azure.Management.DataFactories.Models.AmazonS3Dataset.Compression" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.DataFactories.Models.Compression</ReturnType>
      </ReturnValue>
      <Docs>
        <summary> 
            <span data-ttu-id="08489-105">Die datenkomprimierungsmethode für die Amazon S3-Objekte verwendet.</span><span class="sxs-lookup"><span data-stu-id="08489-105">The data compression method used for the Amazon S3 object(s).</span></span> 
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Format">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.DataFactories.Models.StorageFormat Format { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.DataFactories.Models.StorageFormat Format" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactories.Models.AmazonS3Dataset.Format" />
      <MemberSignature Language="VB.NET" Value="Public Property Format As StorageFormat" />
      <MemberSignature Language="F#" Value="member this.Format : Microsoft.Azure.Management.DataFactories.Models.StorageFormat with get, set" Usage="Microsoft.Azure.Management.DataFactories.Models.AmazonS3Dataset.Format" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.DataFactories.Models.StorageFormat</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="08489-106">Das Format der Amazon S3-Objekte.</span><span class="sxs-lookup"><span data-stu-id="08489-106">The format of the Amazon S3 object(s).</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Key">
      <MemberSignature Language="C#" Value="public string Key { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Key" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactories.Models.AmazonS3Dataset.Key" />
      <MemberSignature Language="VB.NET" Value="Public Property Key As String" />
      <MemberSignature Language="F#" Value="member this.Key : string with get, set" Usage="Microsoft.Azure.Management.DataFactories.Models.AmazonS3Dataset.Key" />
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
            <span data-ttu-id="08489-107">Der Schlüssel des Objekts Amazon S3.</span><span class="sxs-lookup"><span data-stu-id="08489-107">The key of the Amazon S3 object.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Prefix">
      <MemberSignature Language="C#" Value="public string Prefix { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Prefix" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactories.Models.AmazonS3Dataset.Prefix" />
      <MemberSignature Language="VB.NET" Value="Public Property Prefix As String" />
      <MemberSignature Language="F#" Value="member this.Prefix : string with get, set" Usage="Microsoft.Azure.Management.DataFactories.Models.AmazonS3Dataset.Prefix" />
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
            <span data-ttu-id="08489-108">Der präfixfilter für den Namen der S3-Objekte.</span><span class="sxs-lookup"><span data-stu-id="08489-108">The prefix filter for the S3 object(s) name.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Version">
      <MemberSignature Language="C#" Value="public string Version { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Version" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactories.Models.AmazonS3Dataset.Version" />
      <MemberSignature Language="VB.NET" Value="Public Property Version As String" />
      <MemberSignature Language="F#" Value="member this.Version : string with get, set" Usage="Microsoft.Azure.Management.DataFactories.Models.AmazonS3Dataset.Version" />
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
            <span data-ttu-id="08489-109">Die Version für das S3-Objekt.</span><span class="sxs-lookup"><span data-stu-id="08489-109">The version for the S3 object.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>