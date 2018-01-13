<Type Name="HDInsightLinkedService" FullName="Microsoft.Azure.Management.DataFactories.Models.HDInsightLinkedService">
  <TypeSignature Language="C#" Value="public class HDInsightLinkedService : Microsoft.Azure.Management.DataFactories.Models.LinkedServiceTypeProperties" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit HDInsightLinkedService extends Microsoft.Azure.Management.DataFactories.Models.LinkedServiceTypeProperties" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.DataFactories.Models.HDInsightLinkedService" />
  <TypeSignature Language="VB.NET" Value="Public Class HDInsightLinkedService&#xA;Inherits LinkedServiceTypeProperties" />
  <TypeSignature Language="F#" Value="type HDInsightLinkedService = class&#xA;    inherit LinkedServiceTypeProperties" />
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
      <AttributeName>Microsoft.Azure.Management.DataFactories.Models.AdfTypeName("HDInsight")</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            <span data-ttu-id="e6e3c-101">Die Eigenschaften für den HDInsight-LinkedService.</span><span class="sxs-lookup"><span data-stu-id="e6e3c-101">The properties for the HDInsight linkedService.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public HDInsightLinkedService ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.Models.HDInsightLinkedService.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="e6e3c-102">Initialisiert eine neue Instanz der Klasse HDInsightBYOCLinkedService.</span><span class="sxs-lookup"><span data-stu-id="e6e3c-102">Initializes a new instance of the HDInsightBYOCLinkedService class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public HDInsightLinkedService (string clusterUri, string userName, string password);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string clusterUri, string userName, string password) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.Models.HDInsightLinkedService.#ctor(System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (clusterUri As String, userName As String, password As String)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.DataFactories.Models.HDInsightLinkedService : string * string * string -&gt; Microsoft.Azure.Management.DataFactories.Models.HDInsightLinkedService" Usage="new Microsoft.Azure.Management.DataFactories.Models.HDInsightLinkedService (clusterUri, userName, password)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="clusterUri" Type="System.String" />
        <Parameter Name="userName" Type="System.String" />
        <Parameter Name="password" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="clusterUri">To be added.</param>
        <param name="userName">To be added.</param>
        <param name="password">To be added.</param>
        <summary>
            <span data-ttu-id="e6e3c-103">Initialisiert eine neue Instanz der HDInsightBYOCLinkedService-Klasse mit erforderlichen Argumenten.</span><span class="sxs-lookup"><span data-stu-id="e6e3c-103">Initializes a new instance of the HDInsightBYOCLinkedService class with required arguments.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ClusterUri">
      <MemberSignature Language="C#" Value="public string ClusterUri { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ClusterUri" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactories.Models.HDInsightLinkedService.ClusterUri" />
      <MemberSignature Language="VB.NET" Value="Public Property ClusterUri As String" />
      <MemberSignature Language="F#" Value="member this.ClusterUri : string with get, set" Usage="Microsoft.Azure.Management.DataFactories.Models.HDInsightLinkedService.ClusterUri" />
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
            <span data-ttu-id="e6e3c-104">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="e6e3c-104">Required.</span></span> <span data-ttu-id="e6e3c-105">HDInsight-Cluster-URI.</span><span class="sxs-lookup"><span data-stu-id="e6e3c-105">HDInsight cluster URI.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="HcatalogLinkedServiceName">
      <MemberSignature Language="C#" Value="public string HcatalogLinkedServiceName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string HcatalogLinkedServiceName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactories.Models.HDInsightLinkedService.HcatalogLinkedServiceName" />
      <MemberSignature Language="VB.NET" Value="Public Property HcatalogLinkedServiceName As String" />
      <MemberSignature Language="F#" Value="member this.HcatalogLinkedServiceName : string with get, set" Usage="Microsoft.Azure.Management.DataFactories.Models.HDInsightLinkedService.HcatalogLinkedServiceName" />
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
            <span data-ttu-id="e6e3c-106">Der Name des mit Azure SQL verknüpften Diensts, der auf die HCatalog-Datenbank verweist.</span><span class="sxs-lookup"><span data-stu-id="e6e3c-106">The name of Azure SQL linked service that point to the HCatalog database.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="LinkedServiceName">
      <MemberSignature Language="C#" Value="public string LinkedServiceName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string LinkedServiceName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactories.Models.HDInsightLinkedService.LinkedServiceName" />
      <MemberSignature Language="VB.NET" Value="Public Property LinkedServiceName As String" />
      <MemberSignature Language="F#" Value="member this.LinkedServiceName : string with get, set" Usage="Microsoft.Azure.Management.DataFactories.Models.HDInsightLinkedService.LinkedServiceName" />
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
            <span data-ttu-id="e6e3c-107">Optional.</span><span class="sxs-lookup"><span data-stu-id="e6e3c-107">Optional.</span></span> <span data-ttu-id="e6e3c-108">Name des Speicher-Diensts.</span><span class="sxs-lookup"><span data-stu-id="e6e3c-108">Storage service name.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Password">
      <MemberSignature Language="C#" Value="public string Password { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Password" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactories.Models.HDInsightLinkedService.Password" />
      <MemberSignature Language="VB.NET" Value="Public Property Password As String" />
      <MemberSignature Language="F#" Value="member this.Password : string with get, set" Usage="Microsoft.Azure.Management.DataFactories.Models.HDInsightLinkedService.Password" />
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
            <span data-ttu-id="e6e3c-109">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="e6e3c-109">Required.</span></span> <span data-ttu-id="e6e3c-110">HDInsight-Cluster-Kennwort.</span><span class="sxs-lookup"><span data-stu-id="e6e3c-110">HDInsight cluster password.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SchemaGeneration">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.DataFactories.Models.HDInsightSchemaGenerationProperties SchemaGeneration { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.DataFactories.Models.HDInsightSchemaGenerationProperties SchemaGeneration" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactories.Models.HDInsightLinkedService.SchemaGeneration" />
      <MemberSignature Language="VB.NET" Value="Public Property SchemaGeneration As HDInsightSchemaGenerationProperties" />
      <MemberSignature Language="F#" Value="member this.SchemaGeneration : Microsoft.Azure.Management.DataFactories.Models.HDInsightSchemaGenerationProperties with get, set" Usage="Microsoft.Azure.Management.DataFactories.Models.HDInsightLinkedService.SchemaGeneration" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.DataFactories.Models.HDInsightSchemaGenerationProperties</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="e6e3c-111">Definieren, welche Optionen zum Generieren von/Ändern von Eingabe und Ausgabe von Datasets für eine HDInsight-Aktivität</span><span class="sxs-lookup"><span data-stu-id="e6e3c-111">Define what options to use for generating/altering an input and output Datasets for an HDInsight activity</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UserName">
      <MemberSignature Language="C#" Value="public string UserName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string UserName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactories.Models.HDInsightLinkedService.UserName" />
      <MemberSignature Language="VB.NET" Value="Public Property UserName As String" />
      <MemberSignature Language="F#" Value="member this.UserName : string with get, set" Usage="Microsoft.Azure.Management.DataFactories.Models.HDInsightLinkedService.UserName" />
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
            <span data-ttu-id="e6e3c-112">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="e6e3c-112">Required.</span></span> <span data-ttu-id="e6e3c-113">HDInsight-Cluster-Benutzername.</span><span class="sxs-lookup"><span data-stu-id="e6e3c-113">HDInsight cluster user name.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>