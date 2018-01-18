<Type Name="RedshiftUnloadSettings" FullName="Microsoft.Azure.Management.DataFactory.Models.RedshiftUnloadSettings">
  <TypeSignature Language="C#" Value="public class RedshiftUnloadSettings" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit RedshiftUnloadSettings extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.DataFactory.Models.RedshiftUnloadSettings" />
  <TypeSignature Language="VB.NET" Value="Public Class RedshiftUnloadSettings" />
  <TypeSignature Language="F#" Value="type RedshiftUnloadSettings = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
    <AssemblyVersion>0.2.0.0</AssemblyVersion>
    <AssemblyVersion>0.3.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="99cd8-101">Die Amazon S3 Einstellungen für die zwischenzeitliche Amazon S3 beim Kopieren von Amazon Redshift mit entladen zu können.</span><span class="sxs-lookup"><span data-stu-id="99cd8-101">The Amazon S3 settings needed for the interim Amazon S3 when copying from Amazon Redshift with unload.</span></span> <span data-ttu-id="99cd8-102">Mit dieser Option können werden Daten von Amazon Redshift-Quelle zuerst in S3 entladen und dann in die entsprechenden Senke von interim S3 kopiert.</span><span class="sxs-lookup"><span data-stu-id="99cd8-102">With this, data from Amazon Redshift source will be unloaded into S3 first and then copied into the targeted sink from the interim S3.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public RedshiftUnloadSettings ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.Models.RedshiftUnloadSettings.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="99cd8-103">Initialisiert eine neue Instanz der RedshiftUnloadSettings-Klasse.</span><span class="sxs-lookup"><span data-stu-id="99cd8-103">Initializes a new instance of the RedshiftUnloadSettings class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public RedshiftUnloadSettings (Microsoft.Azure.Management.DataFactory.Models.LinkedServiceReference s3LinkedServiceName, object bucketName);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class Microsoft.Azure.Management.DataFactory.Models.LinkedServiceReference s3LinkedServiceName, object bucketName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.Models.RedshiftUnloadSettings.#ctor(Microsoft.Azure.Management.DataFactory.Models.LinkedServiceReference,System.Object)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (s3LinkedServiceName As LinkedServiceReference, bucketName As Object)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.DataFactory.Models.RedshiftUnloadSettings : Microsoft.Azure.Management.DataFactory.Models.LinkedServiceReference * obj -&gt; Microsoft.Azure.Management.DataFactory.Models.RedshiftUnloadSettings" Usage="new Microsoft.Azure.Management.DataFactory.Models.RedshiftUnloadSettings (s3LinkedServiceName, bucketName)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="s3LinkedServiceName" Type="Microsoft.Azure.Management.DataFactory.Models.LinkedServiceReference" />
        <Parameter Name="bucketName" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="s3LinkedServiceName"><span data-ttu-id="99cd8-104">Der Name des Amazon-S3 verknüpft-Diensts, die beim Kopieren der Amazon Redshift-Quelle für der Entladevorgang verwendet wird.</span><span class="sxs-lookup"><span data-stu-id="99cd8-104">The name of the Amazon S3 linked service which will be used for the unload operation when copying from the Amazon Redshift source.</span></span></param>
        <param name="bucketName"><span data-ttu-id="99cd8-105">Der Bucket der zwischenzeitlichen Amazon S3, die zum Speichern der entladen Daten von Amazon Redshift-Quelle verwendet werden soll.</span><span class="sxs-lookup"><span data-stu-id="99cd8-105">The bucket of the interim Amazon S3 which will be used to store the unloaded data from Amazon Redshift source.</span></span> <span data-ttu-id="99cd8-106">Der Bucket muss in der gleichen Region wie der Amazon Redshift-Quelle sein.</span><span class="sxs-lookup"><span data-stu-id="99cd8-106">The bucket must be in the same region as the Amazon Redshift source.</span></span> <span data-ttu-id="99cd8-107">Typ: Zeichenfolge (oder Ausdruck mit ResultType-Zeichenfolge).</span><span class="sxs-lookup"><span data-stu-id="99cd8-107">Type: string (or Expression with resultType string).</span></span></param>
        <summary>
            <span data-ttu-id="99cd8-108">Initialisiert eine neue Instanz der RedshiftUnloadSettings-Klasse.</span><span class="sxs-lookup"><span data-stu-id="99cd8-108">Initializes a new instance of the RedshiftUnloadSettings class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BucketName">
      <MemberSignature Language="C#" Value="public object BucketName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance object BucketName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.RedshiftUnloadSettings.BucketName" />
      <MemberSignature Language="VB.NET" Value="Public Property BucketName As Object" />
      <MemberSignature Language="F#" Value="member this.BucketName : obj with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.RedshiftUnloadSettings.BucketName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="bucketName")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Object</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="99cd8-109">Ruft ab oder legt den Bucket des der zwischenzeitlichen Amazon S3, die zum Speichern der entladen Daten von Amazon Redshift-Quelle verwendet werden soll.</span><span class="sxs-lookup"><span data-stu-id="99cd8-109">Gets or sets the bucket of the interim Amazon S3 which will be used to store the unloaded data from Amazon Redshift source.</span></span> <span data-ttu-id="99cd8-110">Der Bucket muss in der gleichen Region wie der Amazon Redshift-Quelle sein.</span><span class="sxs-lookup"><span data-stu-id="99cd8-110">The bucket must be in the same region as the Amazon Redshift source.</span></span> <span data-ttu-id="99cd8-111">Typ: Zeichenfolge (oder Ausdruck mit ResultType-Zeichenfolge).</span><span class="sxs-lookup"><span data-stu-id="99cd8-111">Type: string (or Expression with resultType string).</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="S3LinkedServiceName">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.DataFactory.Models.LinkedServiceReference S3LinkedServiceName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.DataFactory.Models.LinkedServiceReference S3LinkedServiceName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.RedshiftUnloadSettings.S3LinkedServiceName" />
      <MemberSignature Language="VB.NET" Value="Public Property S3LinkedServiceName As LinkedServiceReference" />
      <MemberSignature Language="F#" Value="member this.S3LinkedServiceName : Microsoft.Azure.Management.DataFactory.Models.LinkedServiceReference with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.RedshiftUnloadSettings.S3LinkedServiceName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="s3LinkedServiceName")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.DataFactory.Models.LinkedServiceReference</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="99cd8-112">Ruft ab oder legt den Namen des Amazon-S3 verknüpft-Diensts, die beim Kopieren der Amazon Redshift-Quelle für der Entladevorgang verwendet wird.</span><span class="sxs-lookup"><span data-stu-id="99cd8-112">Gets or sets the name of the Amazon S3 linked service which will be used for the unload operation when copying from the Amazon Redshift source.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.Models.RedshiftUnloadSettings.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="redshiftUnloadSettings.Validate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="99cd8-113">Überprüfen Sie das Objekt.</span><span class="sxs-lookup"><span data-stu-id="99cd8-113">Validate the object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="99cd8-114">Wird ausgelöst, wenn die Validierung fehlschlägt</span><span class="sxs-lookup"><span data-stu-id="99cd8-114">Thrown if validation fails</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>