<Type Name="ServiceRuntime" FullName="Microsoft.ServiceFabric.Services.Runtime.ServiceRuntime">
  <TypeSignature Language="C#" Value="public static class ServiceRuntime" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit ServiceRuntime extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceFabric.Services.Runtime.ServiceRuntime" />
  <TypeSignature Language="VB.NET" Value="Public Class ServiceRuntime" />
  <TypeSignature Language="F#" Value="type ServiceRuntime = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.ServiceFabric.Services</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="5c0f4-101">Die statische Klasse, die Methoden zum Registrieren von zuverlässige Dienste mit Service Fabric-Laufzeit bereitstellt.</span><span class="sxs-lookup"><span data-stu-id="5c0f4-101">The static class that provides methods to register reliable services with Service Fabric runtime.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="RegisterServiceAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task RegisterServiceAsync (string serviceTypeName, Func&lt;System.Fabric.StatefulServiceContext,Microsoft.ServiceFabric.Services.Runtime.StatefulServiceBase&gt; serviceFactory, TimeSpan timeout = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task RegisterServiceAsync(string serviceTypeName, class System.Func`2&lt;class System.Fabric.StatefulServiceContext, class Microsoft.ServiceFabric.Services.Runtime.StatefulServiceBase&gt; serviceFactory, valuetype System.TimeSpan timeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Services.Runtime.ServiceRuntime.RegisterServiceAsync(System.String,System.Func{System.Fabric.StatefulServiceContext,Microsoft.ServiceFabric.Services.Runtime.StatefulServiceBase},System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member RegisterServiceAsync : string * Func&lt;System.Fabric.StatefulServiceContext, Microsoft.ServiceFabric.Services.Runtime.StatefulServiceBase&gt; * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.ServiceFabric.Services.Runtime.ServiceRuntime.RegisterServiceAsync (serviceTypeName, serviceFactory, timeout, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.ServiceFabric.Services.Runtime.ServiceRuntime/&lt;RegisterServiceAsync&gt;d__1))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="serviceTypeName" Type="System.String" />
        <Parameter Name="serviceFactory" Type="System.Func&lt;System.Fabric.StatefulServiceContext,Microsoft.ServiceFabric.Services.Runtime.StatefulServiceBase&gt;" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="serviceTypeName"><span data-ttu-id="5c0f4-102">Der Diensttypname als Ressourcenanbieter im Dienst manifest.</span><span class="sxs-lookup"><span data-stu-id="5c0f4-102">The service type name as provied in service manifest.</span></span></param>
        <param name="serviceFactory"><span data-ttu-id="5c0f4-103">Eine Factorymethode zum Erstellen von Objekten mit einem zustandsbehafteten Dienst.</span><span class="sxs-lookup"><span data-stu-id="5c0f4-103">A factory method to create stateful service objects.</span></span></param>
        <param name="timeout"><span data-ttu-id="5c0f4-104">Das Timeout für den Registrierungsvorgang.</span><span class="sxs-lookup"><span data-stu-id="5c0f4-104">The timeout for the register operation.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="5c0f4-105">Das Token zum überwachen von Abbruchanforderungen.</span><span class="sxs-lookup"><span data-stu-id="5c0f4-105">The token to monitor for cancellation requests.</span></span></param>
        <summary>
            <span data-ttu-id="5c0f4-106">Registriert eine zuverlässige stateful Service mit Service Fabric-Laufzeit.</span><span class="sxs-lookup"><span data-stu-id="5c0f4-106">Registers a reliable stateful service with Service Fabric runtime.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="5c0f4-107">Eine Aufgabe, die den asynchronen Registrierungsvorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="5c0f4-107">A task that represents the asynchronous register operation.</span></span>
            </returns>
        <remarks>To be added.</remarks>
        <para><span data-ttu-id="5c0f4-108">Das Standardtimeout für diesen Vorgang wird vom ServiceFactoryRegistrationTimeout im Hosting-Abschnitt, der das clustermanifest übernommen.</span><span class="sxs-lookup"><span data-stu-id="5c0f4-108">The default timeout for this operation is taken from ServiceFactoryRegistrationTimeout in Hosting section of the cluster manifest.</span></span> <span data-ttu-id="5c0f4-109">Standardwert für ServiceFactoryRegistrationTimeout ist 120 Sekunden.</span><span class="sxs-lookup"><span data-stu-id="5c0f4-109">Default value for ServiceFactoryRegistrationTimeout is 120 seconds.</span></span></para>
      </Docs>
    </Member>
    <Member MemberName="RegisterServiceAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task RegisterServiceAsync (string serviceTypeName, Func&lt;System.Fabric.StatelessServiceContext,Microsoft.ServiceFabric.Services.Runtime.StatelessService&gt; serviceFactory, TimeSpan timeout = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task RegisterServiceAsync(string serviceTypeName, class System.Func`2&lt;class System.Fabric.StatelessServiceContext, class Microsoft.ServiceFabric.Services.Runtime.StatelessService&gt; serviceFactory, valuetype System.TimeSpan timeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Services.Runtime.ServiceRuntime.RegisterServiceAsync(System.String,System.Func{System.Fabric.StatelessServiceContext,Microsoft.ServiceFabric.Services.Runtime.StatelessService},System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member RegisterServiceAsync : string * Func&lt;System.Fabric.StatelessServiceContext, Microsoft.ServiceFabric.Services.Runtime.StatelessService&gt; * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.ServiceFabric.Services.Runtime.ServiceRuntime.RegisterServiceAsync (serviceTypeName, serviceFactory, timeout, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.ServiceFabric.Services.Runtime.ServiceRuntime/&lt;RegisterServiceAsync&gt;d__0))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="serviceTypeName" Type="System.String" />
        <Parameter Name="serviceFactory" Type="System.Func&lt;System.Fabric.StatelessServiceContext,Microsoft.ServiceFabric.Services.Runtime.StatelessService&gt;" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="serviceTypeName"><span data-ttu-id="5c0f4-110">Der Diensttypname als Ressourcenanbieter im Dienst manifest.</span><span class="sxs-lookup"><span data-stu-id="5c0f4-110">The service type name as provied in service manifest.</span></span></param>
        <param name="serviceFactory"><span data-ttu-id="5c0f4-111">Eine Factorymethode zum Erstellen von Objekten zustandslosen Diensts.</span><span class="sxs-lookup"><span data-stu-id="5c0f4-111">A factory method to create stateless service objects.</span></span></param>
        <param name="timeout"><span data-ttu-id="5c0f4-112">Das Timeout für den Registrierungsvorgang.</span><span class="sxs-lookup"><span data-stu-id="5c0f4-112">The timeout for the register operation.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="5c0f4-113">Das Token zum überwachen von Abbruchanforderungen.</span><span class="sxs-lookup"><span data-stu-id="5c0f4-113">The token to monitor for cancellation requests.</span></span></param>
        <summary>
            <span data-ttu-id="5c0f4-114">Registriert eine zuverlässige zustandslosen Diensts mit Service Fabric-Laufzeit.</span><span class="sxs-lookup"><span data-stu-id="5c0f4-114">Registers a reliable stateless service with Service Fabric runtime.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="5c0f4-115">Eine Aufgabe, die den asynchronen Registrierungsvorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="5c0f4-115">A task that represents the asynchronous register operation.</span></span>
            </returns>
        <remarks>To be added.</remarks>
        <para><span data-ttu-id="5c0f4-116">Das Standardtimeout für diesen Vorgang wird vom ServiceFactoryRegistrationTimeout im Hosting-Abschnitt, der das clustermanifest übernommen.</span><span class="sxs-lookup"><span data-stu-id="5c0f4-116">The default timeout for this operation is taken from ServiceFactoryRegistrationTimeout in Hosting section of the cluster manifest.</span></span> <span data-ttu-id="5c0f4-117">Standardwert für ServiceFactoryRegistrationTimeout ist 120 Sekunden.</span><span class="sxs-lookup"><span data-stu-id="5c0f4-117">Default value for ServiceFactoryRegistrationTimeout is 120 seconds.</span></span></para>
      </Docs>
    </Member>
  </Members>
</Type>