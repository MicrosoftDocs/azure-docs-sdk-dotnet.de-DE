<Type Name="ComposeDeploymentStatusQueryDescription" FullName="Microsoft.ServiceFabric.Preview.Client.Description.ComposeDeploymentStatusQueryDescription">
  <TypeSignature Language="C#" Value="public sealed class ComposeDeploymentStatusQueryDescription" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit ComposeDeploymentStatusQueryDescription extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceFabric.Preview.Client.Description.ComposeDeploymentStatusQueryDescription" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class ComposeDeploymentStatusQueryDescription" />
  <TypeSignature Language="F#" Value="type ComposeDeploymentStatusQueryDescription = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.ServiceFabric.Preview</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
      <para><span data-ttu-id="c3700-101">Stellt die abfrageeingabe von System.Fabric.FabricClient.ComposeDeploymentClient.GetComposeDeploymentStatusPagedListAsync(Microsoft.ServiceFabric.Preview.Client.Description.ComposeDeploymentStatusQueryDescription) verwendet.</span><span class="sxs-lookup"><span data-stu-id="c3700-101">Represents the query input used by System.Fabric.FabricClient.ComposeDeploymentClient.GetComposeDeploymentStatusPagedListAsync(Microsoft.ServiceFabric.Preview.Client.Description.ComposeDeploymentStatusQueryDescription) .</span></span></para>
    </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ComposeDeploymentStatusQueryDescription ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Preview.Client.Description.ComposeDeploymentStatusQueryDescription.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Preview</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
          <para><span data-ttu-id="c3700-102">Instanziiert eine Instanz des <see cref="T:Microsoft.ServiceFabric.Preview.Client.Description.ComposeDeploymentStatusQueryDescription" /> Klasse.</span><span class="sxs-lookup"><span data-stu-id="c3700-102">Instantiates an instance of <see cref="T:Microsoft.ServiceFabric.Preview.Client.Description.ComposeDeploymentStatusQueryDescription" /> class.</span></span></para>
        </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ContinuationToken">
      <MemberSignature Language="C#" Value="public string ContinuationToken { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ContinuationToken" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceFabric.Preview.Client.Description.ComposeDeploymentStatusQueryDescription.ContinuationToken" />
      <MemberSignature Language="VB.NET" Value="Public Property ContinuationToken As String" />
      <MemberSignature Language="F#" Value="member this.ContinuationToken : string with get, set" Usage="Microsoft.ServiceFabric.Preview.Client.Description.ComposeDeploymentStatusQueryDescription.ContinuationToken" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Preview</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para><span data-ttu-id="c3700-103">Ruft ab oder legt das Token, das zum Abrufen der nächsten Seite von Abfragen verwendet werden kann.</span><span class="sxs-lookup"><span data-stu-id="c3700-103">Gets or sets the token that can be used by queries to get the next page.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="c3700-104">Das Token, das zum Abrufen der nächsten Seite von Abfragen verwendet werden kann.</span><span class="sxs-lookup"><span data-stu-id="c3700-104">The token that can be used by queries to get the next page.</span></span></para>
        </value>
        <remarks>
          <para><span data-ttu-id="c3700-105">ContinuationToken wird von einer vorherigen Abfrage empfangen.</span><span class="sxs-lookup"><span data-stu-id="c3700-105">ContinuationToken is received by a previous query.</span></span></para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="DeploymentNameFilter">
      <MemberSignature Language="C#" Value="public string DeploymentNameFilter { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string DeploymentNameFilter" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceFabric.Preview.Client.Description.ComposeDeploymentStatusQueryDescription.DeploymentNameFilter" />
      <MemberSignature Language="VB.NET" Value="Public Property DeploymentNameFilter As String" />
      <MemberSignature Language="F#" Value="member this.DeploymentNameFilter : string with get, set" Usage="Microsoft.ServiceFabric.Preview.Client.Description.ComposeDeploymentStatusQueryDescription.DeploymentNameFilter" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Preview</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para><span data-ttu-id="c3700-106">Ruft ab oder legt der Namen der Bereitstellung, bei der Abfrage bilden.</span><span class="sxs-lookup"><span data-stu-id="c3700-106">Gets or sets the name of compose deployment to query for.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="c3700-107">Der Name des bilden Bereitstellung bei der Abfrage.</span><span class="sxs-lookup"><span data-stu-id="c3700-107">The name of compose deployment to query for.</span></span></para>
        </value>
        <remarks>
          <para> <span data-ttu-id="c3700-108">Wenn DeploymentNameFilter nicht angegeben wird, bilden alle Bereitstellungen zurückgegeben werden.</span><span class="sxs-lookup"><span data-stu-id="c3700-108">If DeploymentNameFilter is not specified, all compose deployments are returned.</span></span></para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="MaxResults">
      <MemberSignature Language="C#" Value="public long MaxResults { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 MaxResults" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceFabric.Preview.Client.Description.ComposeDeploymentStatusQueryDescription.MaxResults" />
      <MemberSignature Language="VB.NET" Value="Public Property MaxResults As Long" />
      <MemberSignature Language="F#" Value="member this.MaxResults : int64 with get, set" Usage="Microsoft.ServiceFabric.Preview.Client.Description.ComposeDeploymentStatusQueryDescription.MaxResults" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Preview</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int64</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="c3700-109">Ruft ab oder legt die maximale Anzahl von Microsoft.ServiceFabric.Preview.Client.Query.ComposeDeploymentStatusResultItems, die pro Seite zurückgegeben werden können.</span><span class="sxs-lookup"><span data-stu-id="c3700-109">Gets or sets the max number of Microsoft.ServiceFabric.Preview.Client.Query.ComposeDeploymentStatusResultItems that can be returned per page.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
          <para>
            <span data-ttu-id="c3700-110">Wenn dieser Wert nicht festgelegt ist, wird es nicht verwendet, um die Anzahl der zurückgegebenen Microsoft.ServiceFabric.Preview.Client.Query.ComposeDeploymentStatusResultItems zu beschränken.</span><span class="sxs-lookup"><span data-stu-id="c3700-110">If this value is not set, it is not used to limit the number of returned Microsoft.ServiceFabric.Preview.Client.Query.ComposeDeploymentStatusResultItems.</span></span>
            </para>
        </remarks>
      </Docs>
    </Member>
  </Members>
</Type>