<Type Name="UsageOperationsExtensions" FullName="Microsoft.Azure.Management.Compute.UsageOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class UsageOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit UsageOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Compute.UsageOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module UsageOperationsExtensions" />
  <TypeSignature Language="F#" Value="type UsageOperationsExtensions = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
    <AssemblyVersion>16.0.0.0</AssemblyVersion>
    <AssemblyVersion>17.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="94595-101">Erweiterungsmethoden für UsageOperations.</span><span class="sxs-lookup"><span data-stu-id="94595-101">Extension methods for UsageOperations.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="List">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Compute.Models.Usage&gt; List (this Microsoft.Azure.Management.Compute.IUsageOperations operations, string location);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Compute.Models.Usage&gt; List(class Microsoft.Azure.Management.Compute.IUsageOperations operations, string location) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.UsageOperationsExtensions.List(Microsoft.Azure.Management.Compute.IUsageOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function List (operations As IUsageOperations, location As String) As IPage(Of Usage)" />
      <MemberSignature Language="F#" Value="static member List : Microsoft.Azure.Management.Compute.IUsageOperations * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Compute.Models.Usage&gt;" Usage="Microsoft.Azure.Management.Compute.UsageOperationsExtensions.List (operations, location)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Compute.Models.Usage&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Compute.IUsageOperations" RefType="this" />
        <Parameter Name="location" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="94595-102">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="94595-102">The operations group for this extension method.</span></span>
            </param>
        <param name="location">
            <span data-ttu-id="94595-103">Der Speicherort, für welche, den Ressource Nutzung abgefragt wird.</span><span class="sxs-lookup"><span data-stu-id="94595-103">The location for which resource usage is queried.</span></span>
            </param>
        <summary>
            <span data-ttu-id="94595-104">Ruft ab, für den angegebenen Speicherort, der aktuelle Nutzungsinformationen der Compute-Ressource sowie die Grenzwerte für die Serverressourcen unter dem Abonnement ein.</span><span class="sxs-lookup"><span data-stu-id="94595-104">Gets, for the specified location, the current compute resource usage information as well as the limits for compute resources under the subscription.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Compute.Models.Usage&gt;&gt; ListAsync (this Microsoft.Azure.Management.Compute.IUsageOperations operations, string location, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Compute.Models.Usage&gt;&gt; ListAsync(class Microsoft.Azure.Management.Compute.IUsageOperations operations, string location, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.UsageOperationsExtensions.ListAsync(Microsoft.Azure.Management.Compute.IUsageOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListAsync : Microsoft.Azure.Management.Compute.IUsageOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Compute.Models.Usage&gt;&gt;" Usage="Microsoft.Azure.Management.Compute.UsageOperationsExtensions.ListAsync (operations, location, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Compute.UsageOperationsExtensions/&lt;ListAsync&gt;d__1))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Compute.Models.Usage&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Compute.IUsageOperations" RefType="this" />
        <Parameter Name="location" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="94595-105">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="94595-105">The operations group for this extension method.</span></span>
            </param>
        <param name="location">
            <span data-ttu-id="94595-106">Der Speicherort, für welche, den Ressource Nutzung abgefragt wird.</span><span class="sxs-lookup"><span data-stu-id="94595-106">The location for which resource usage is queried.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="94595-107">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="94595-107">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="94595-108">Ruft ab, für den angegebenen Speicherort, der aktuelle Nutzungsinformationen der Compute-Ressource sowie die Grenzwerte für die Serverressourcen unter dem Abonnement ein.</span><span class="sxs-lookup"><span data-stu-id="94595-108">Gets, for the specified location, the current compute resource usage information as well as the limits for compute resources under the subscription.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListNext">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Compute.Models.Usage&gt; ListNext (this Microsoft.Azure.Management.Compute.IUsageOperations operations, string nextPageLink);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Compute.Models.Usage&gt; ListNext(class Microsoft.Azure.Management.Compute.IUsageOperations operations, string nextPageLink) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.UsageOperationsExtensions.ListNext(Microsoft.Azure.Management.Compute.IUsageOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListNext (operations As IUsageOperations, nextPageLink As String) As IPage(Of Usage)" />
      <MemberSignature Language="F#" Value="static member ListNext : Microsoft.Azure.Management.Compute.IUsageOperations * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Compute.Models.Usage&gt;" Usage="Microsoft.Azure.Management.Compute.UsageOperationsExtensions.ListNext (operations, nextPageLink)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Compute.Models.Usage&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Compute.IUsageOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="94595-109">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="94595-109">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="94595-110">Die "NextLink" aus dem vorherigen erfolgreichen Aufruf List-Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="94595-110">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <summary>
            <span data-ttu-id="94595-111">Ruft ab, für den angegebenen Speicherort, der aktuelle Nutzungsinformationen der Compute-Ressource sowie die Grenzwerte für die Serverressourcen unter dem Abonnement ein.</span><span class="sxs-lookup"><span data-stu-id="94595-111">Gets, for the specified location, the current compute resource usage information as well as the limits for compute resources under the subscription.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Compute.Models.Usage&gt;&gt; ListNextAsync (this Microsoft.Azure.Management.Compute.IUsageOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Compute.Models.Usage&gt;&gt; ListNextAsync(class Microsoft.Azure.Management.Compute.IUsageOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.UsageOperationsExtensions.ListNextAsync(Microsoft.Azure.Management.Compute.IUsageOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListNextAsync : Microsoft.Azure.Management.Compute.IUsageOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Compute.Models.Usage&gt;&gt;" Usage="Microsoft.Azure.Management.Compute.UsageOperationsExtensions.ListNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Compute.UsageOperationsExtensions/&lt;ListNextAsync&gt;d__3))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Compute.Models.Usage&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Compute.IUsageOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="94595-112">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="94595-112">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="94595-113">Die "NextLink" aus dem vorherigen erfolgreichen Aufruf List-Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="94595-113">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="94595-114">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="94595-114">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="94595-115">Ruft ab, für den angegebenen Speicherort, der aktuelle Nutzungsinformationen der Compute-Ressource sowie die Grenzwerte für die Serverressourcen unter dem Abonnement ein.</span><span class="sxs-lookup"><span data-stu-id="94595-115">Gets, for the specified location, the current compute resource usage information as well as the limits for compute resources under the subscription.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>