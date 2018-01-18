<Type Name="IQuery" FullName="Microsoft.Azure.Devices.IQuery">
  <TypeSignature Language="C#" Value="public interface IQuery" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IQuery" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Devices.IQuery" />
  <TypeSignature Language="VB.NET" Value="Public Interface IQuery" />
  <TypeSignature Language="F#" Value="type IQuery = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Devices</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>To be added.</summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="GetNextAsDeviceJobAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Devices.DeviceJob&gt;&gt; GetNextAsDeviceJobAsync ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Devices.DeviceJob&gt;&gt; GetNextAsDeviceJobAsync() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Devices.IQuery.GetNextAsDeviceJobAsync" />
      <MemberSignature Language="VB.NET" Value="Public Function GetNextAsDeviceJobAsync () As Task(Of IEnumerable(Of DeviceJob))" />
      <MemberSignature Language="F#" Value="abstract member GetNextAsDeviceJobAsync : unit -&gt; System.Threading.Tasks.Task&lt;seq&lt;Microsoft.Azure.Devices.DeviceJob&gt;&gt;" Usage="iQuery.GetNextAsDeviceJobAsync " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Devices.DeviceJob&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="f7766-101">Ruft die nächste ausgelagerten Ergebnisses als <see cref="T:Microsoft.Azure.Devices.DeviceJob" /> Objekte</span><span class="sxs-lookup"><span data-stu-id="f7766-101">Retrieves the next paged result as <see cref="T:Microsoft.Azure.Devices.DeviceJob" /> objects</span></span>
            </summary>
        <returns><span data-ttu-id="f7766-102">Liste der <see cref="T:Microsoft.Azure.Devices.DeviceJob" /> Objekte</span><span class="sxs-lookup"><span data-stu-id="f7766-102">List of <see cref="T:Microsoft.Azure.Devices.DeviceJob" /> objects</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetNextAsDeviceJobAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Devices.QueryResponse&lt;Microsoft.Azure.Devices.DeviceJob&gt;&gt; GetNextAsDeviceJobAsync (Microsoft.Azure.Devices.QueryOptions options);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Devices.QueryResponse`1&lt;class Microsoft.Azure.Devices.DeviceJob&gt;&gt; GetNextAsDeviceJobAsync(class Microsoft.Azure.Devices.QueryOptions options) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Devices.IQuery.GetNextAsDeviceJobAsync(Microsoft.Azure.Devices.QueryOptions)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetNextAsDeviceJobAsync (options As QueryOptions) As Task(Of QueryResponse(Of DeviceJob))" />
      <MemberSignature Language="F#" Value="abstract member GetNextAsDeviceJobAsync : Microsoft.Azure.Devices.QueryOptions -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Devices.QueryResponse&lt;Microsoft.Azure.Devices.DeviceJob&gt;&gt;" Usage="iQuery.GetNextAsDeviceJobAsync options" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Devices.QueryResponse&lt;Microsoft.Azure.Devices.DeviceJob&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="options" Type="Microsoft.Azure.Devices.QueryOptions" />
      </Parameters>
      <Docs>
        <param name="options"><span data-ttu-id="f7766-103">Abfrageoptionen</span><span class="sxs-lookup"><span data-stu-id="f7766-103">Query options</span></span></param>
        <summary>
            <span data-ttu-id="f7766-104">Ruft die nächste ausgelagerten Ergebnisses als <see cref="T:Microsoft.Azure.Devices.DeviceJob" /> Objekte</span><span class="sxs-lookup"><span data-stu-id="f7766-104">Retrieves the next paged result as <see cref="T:Microsoft.Azure.Devices.DeviceJob" /> objects</span></span>
            </summary>
        <returns><span data-ttu-id="f7766-105">Ein aufzählbares Element <see cref="T:Microsoft.Azure.Devices.QueryResponse`1" /> Objekt</span><span class="sxs-lookup"><span data-stu-id="f7766-105">An enumerable <see cref="T:Microsoft.Azure.Devices.QueryResponse`1" /> object</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetNextAsJobResponseAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Devices.JobResponse&gt;&gt; GetNextAsJobResponseAsync ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Devices.JobResponse&gt;&gt; GetNextAsJobResponseAsync() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Devices.IQuery.GetNextAsJobResponseAsync" />
      <MemberSignature Language="VB.NET" Value="Public Function GetNextAsJobResponseAsync () As Task(Of IEnumerable(Of JobResponse))" />
      <MemberSignature Language="F#" Value="abstract member GetNextAsJobResponseAsync : unit -&gt; System.Threading.Tasks.Task&lt;seq&lt;Microsoft.Azure.Devices.JobResponse&gt;&gt;" Usage="iQuery.GetNextAsJobResponseAsync " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Devices.JobResponse&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="f7766-106">Ruft die nächste ausgelagerten Ergebnisses als <see cref="T:Microsoft.Azure.Devices.JobResponse" /> Objekte</span><span class="sxs-lookup"><span data-stu-id="f7766-106">Retrieves the next paged result as <see cref="T:Microsoft.Azure.Devices.JobResponse" /> objects</span></span>
            </summary>
        <returns><span data-ttu-id="f7766-107">Liste der <see cref="T:Microsoft.Azure.Devices.JobResponse" /> Objekte</span><span class="sxs-lookup"><span data-stu-id="f7766-107">List of <see cref="T:Microsoft.Azure.Devices.JobResponse" /> objects</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetNextAsJobResponseAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Devices.QueryResponse&lt;Microsoft.Azure.Devices.JobResponse&gt;&gt; GetNextAsJobResponseAsync (Microsoft.Azure.Devices.QueryOptions options);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Devices.QueryResponse`1&lt;class Microsoft.Azure.Devices.JobResponse&gt;&gt; GetNextAsJobResponseAsync(class Microsoft.Azure.Devices.QueryOptions options) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Devices.IQuery.GetNextAsJobResponseAsync(Microsoft.Azure.Devices.QueryOptions)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetNextAsJobResponseAsync (options As QueryOptions) As Task(Of QueryResponse(Of JobResponse))" />
      <MemberSignature Language="F#" Value="abstract member GetNextAsJobResponseAsync : Microsoft.Azure.Devices.QueryOptions -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Devices.QueryResponse&lt;Microsoft.Azure.Devices.JobResponse&gt;&gt;" Usage="iQuery.GetNextAsJobResponseAsync options" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Devices.QueryResponse&lt;Microsoft.Azure.Devices.JobResponse&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="options" Type="Microsoft.Azure.Devices.QueryOptions" />
      </Parameters>
      <Docs>
        <param name="options"><span data-ttu-id="f7766-108">Abfrageoptionen</span><span class="sxs-lookup"><span data-stu-id="f7766-108">Query options</span></span></param>
        <summary>
            <span data-ttu-id="f7766-109">Ruft die nächste ausgelagerten Ergebnisses als <see cref="T:Microsoft.Azure.Devices.JobResponse" /> Objekte</span><span class="sxs-lookup"><span data-stu-id="f7766-109">Retrieves the next paged result as <see cref="T:Microsoft.Azure.Devices.JobResponse" /> objects</span></span>
            </summary>
        <returns><span data-ttu-id="f7766-110">Ein aufzählbares Element <see cref="T:Microsoft.Azure.Devices.QueryResponse`1" /> Objekt</span><span class="sxs-lookup"><span data-stu-id="f7766-110">An enumerable <see cref="T:Microsoft.Azure.Devices.QueryResponse`1" /> object</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetNextAsJsonAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;string&gt;&gt; GetNextAsJsonAsync ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class System.Collections.Generic.IEnumerable`1&lt;string&gt;&gt; GetNextAsJsonAsync() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Devices.IQuery.GetNextAsJsonAsync" />
      <MemberSignature Language="VB.NET" Value="Public Function GetNextAsJsonAsync () As Task(Of IEnumerable(Of String))" />
      <MemberSignature Language="F#" Value="abstract member GetNextAsJsonAsync : unit -&gt; System.Threading.Tasks.Task&lt;seq&lt;string&gt;&gt;" Usage="iQuery.GetNextAsJsonAsync " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;System.String&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="f7766-111">Ruft die nächste ausgelagerten Ergebnisses als JSON-Zeichenfolgen ab</span><span class="sxs-lookup"><span data-stu-id="f7766-111">Retrieves the next paged result as JSON strings</span></span>
            </summary>
        <returns><span data-ttu-id="f7766-112">Liste von JSON-Zeichenfolgen</span><span class="sxs-lookup"><span data-stu-id="f7766-112">List of JSON strings</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetNextAsJsonAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Devices.QueryResponse&lt;string&gt;&gt; GetNextAsJsonAsync (Microsoft.Azure.Devices.QueryOptions options);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Devices.QueryResponse`1&lt;string&gt;&gt; GetNextAsJsonAsync(class Microsoft.Azure.Devices.QueryOptions options) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Devices.IQuery.GetNextAsJsonAsync(Microsoft.Azure.Devices.QueryOptions)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetNextAsJsonAsync (options As QueryOptions) As Task(Of QueryResponse(Of String))" />
      <MemberSignature Language="F#" Value="abstract member GetNextAsJsonAsync : Microsoft.Azure.Devices.QueryOptions -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Devices.QueryResponse&lt;string&gt;&gt;" Usage="iQuery.GetNextAsJsonAsync options" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Devices.QueryResponse&lt;System.String&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="options" Type="Microsoft.Azure.Devices.QueryOptions" />
      </Parameters>
      <Docs>
        <param name="options"><span data-ttu-id="f7766-113">Abfrageoptionen</span><span class="sxs-lookup"><span data-stu-id="f7766-113">Query options</span></span></param>
        <summary>
            <span data-ttu-id="f7766-114">Ruft die nächste ausgelagerten Ergebnisses als JSON-Zeichenfolgen ab</span><span class="sxs-lookup"><span data-stu-id="f7766-114">Retrieves the next paged result as JSON strings</span></span>
            </summary>
        <returns><span data-ttu-id="f7766-115">Ein aufzählbares Element <see cref="T:Microsoft.Azure.Devices.QueryResponse`1" /> Objekt</span><span class="sxs-lookup"><span data-stu-id="f7766-115">An enumerable <see cref="T:Microsoft.Azure.Devices.QueryResponse`1" /> object</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetNextAsTwinAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Devices.Shared.Twin&gt;&gt; GetNextAsTwinAsync ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Devices.Shared.Twin&gt;&gt; GetNextAsTwinAsync() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Devices.IQuery.GetNextAsTwinAsync" />
      <MemberSignature Language="VB.NET" Value="Public Function GetNextAsTwinAsync () As Task(Of IEnumerable(Of Twin))" />
      <MemberSignature Language="F#" Value="abstract member GetNextAsTwinAsync : unit -&gt; System.Threading.Tasks.Task&lt;seq&lt;Microsoft.Azure.Devices.Shared.Twin&gt;&gt;" Usage="iQuery.GetNextAsTwinAsync " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Devices.Shared.Twin&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="f7766-116">Ruft die nächste ausgelagerten Ergebnisses als <see cref="T:Microsoft.Azure.Devices.Shared.Twin" /> Objekte</span><span class="sxs-lookup"><span data-stu-id="f7766-116">Retrieves the next paged result as <see cref="T:Microsoft.Azure.Devices.Shared.Twin" /> objects</span></span>
            </summary>
        <returns><span data-ttu-id="f7766-117">Liste der <see cref="T:Microsoft.Azure.Devices.Shared.Twin" /> Objekte</span><span class="sxs-lookup"><span data-stu-id="f7766-117">List of <see cref="T:Microsoft.Azure.Devices.Shared.Twin" /> objects</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetNextAsTwinAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Devices.QueryResponse&lt;Microsoft.Azure.Devices.Shared.Twin&gt;&gt; GetNextAsTwinAsync (Microsoft.Azure.Devices.QueryOptions options);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Devices.QueryResponse`1&lt;class Microsoft.Azure.Devices.Shared.Twin&gt;&gt; GetNextAsTwinAsync(class Microsoft.Azure.Devices.QueryOptions options) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Devices.IQuery.GetNextAsTwinAsync(Microsoft.Azure.Devices.QueryOptions)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetNextAsTwinAsync (options As QueryOptions) As Task(Of QueryResponse(Of Twin))" />
      <MemberSignature Language="F#" Value="abstract member GetNextAsTwinAsync : Microsoft.Azure.Devices.QueryOptions -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Devices.QueryResponse&lt;Microsoft.Azure.Devices.Shared.Twin&gt;&gt;" Usage="iQuery.GetNextAsTwinAsync options" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Devices.QueryResponse&lt;Microsoft.Azure.Devices.Shared.Twin&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="options" Type="Microsoft.Azure.Devices.QueryOptions" />
      </Parameters>
      <Docs>
        <param name="options"><span data-ttu-id="f7766-118">Abfrageoptionen</span><span class="sxs-lookup"><span data-stu-id="f7766-118">Query options</span></span></param>
        <summary>
            <span data-ttu-id="f7766-119">Ruft die nächste ausgelagerten Ergebnisses als <see cref="T:Microsoft.Azure.Devices.Shared.Twin" /> Objekte</span><span class="sxs-lookup"><span data-stu-id="f7766-119">Retrieves the next paged result as <see cref="T:Microsoft.Azure.Devices.Shared.Twin" /> objects</span></span>
            </summary>
        <returns><span data-ttu-id="f7766-120">Ein aufzählbares Element <see cref="T:Microsoft.Azure.Devices.QueryResponse`1" /> Objekt</span><span class="sxs-lookup"><span data-stu-id="f7766-120">An enumerable <see cref="T:Microsoft.Azure.Devices.QueryResponse`1" /> object</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="HasMoreResults">
      <MemberSignature Language="C#" Value="public bool HasMoreResults { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool HasMoreResults" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Devices.IQuery.HasMoreResults" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property HasMoreResults As Boolean" />
      <MemberSignature Language="F#" Value="member this.HasMoreResults : bool" Usage="Microsoft.Azure.Devices.IQuery.HasMoreResults" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
                <span data-ttu-id="f7766-121">Geben Sie an, ob weitere Ergebnisse abgerufen werden können</span><span class="sxs-lookup"><span data-stu-id="f7766-121">Indicate if more results can be fetched</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>