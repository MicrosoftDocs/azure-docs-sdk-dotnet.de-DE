<Type Name="ServiceNameFormat" FullName="Microsoft.ServiceFabric.Services.ServiceNameFormat">
  <TypeSignature Language="C#" Value="public static class ServiceNameFormat" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit ServiceNameFormat extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceFabric.Services.ServiceNameFormat" />
  <TypeSignature Language="VB.NET" Value="Public Class ServiceNameFormat" />
  <TypeSignature Language="F#" Value="type ServiceNameFormat = class" />
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
            <span data-ttu-id="006e4-101">Diese Klasse stellt die Logik für die Namen der verschiedenen Elemente in der Manifestdatei aus dem Code ableiten.</span><span class="sxs-lookup"><span data-stu-id="006e4-101">This class provides the logic for deriving the names of various items within the manifest from the code.</span></span> <span data-ttu-id="006e4-102">Es wird von Framework-Komponenten verwendet, wenn Namen in der API nicht angegeben sind und die Framework-Typen sie einen aussagekräftigen Namen, der den Diensttyp abgeleitet standardmäßig müssen.</span><span class="sxs-lookup"><span data-stu-id="006e4-102">It is used by framework components when names are not specified in the API and the framework types have to default it to a meaningful name derived from the service type.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="GetEndpointName">
      <MemberSignature Language="C#" Value="public static string GetEndpointName (Type serviceInterfaceType);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig string GetEndpointName(class System.Type serviceInterfaceType) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Services.ServiceNameFormat.GetEndpointName(System.Type)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function GetEndpointName (serviceInterfaceType As Type) As String" />
      <MemberSignature Language="F#" Value="static member GetEndpointName : Type -&gt; string" Usage="Microsoft.ServiceFabric.Services.ServiceNameFormat.GetEndpointName serviceInterfaceType" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="serviceInterfaceType" Type="System.Type" />
      </Parameters>
      <Docs>
        <param name="serviceInterfaceType"><span data-ttu-id="006e4-103">Diensttypname-Schnittstelle.</span><span class="sxs-lookup"><span data-stu-id="006e4-103">Service interface type name.</span></span></param>
        <summary>
            <span data-ttu-id="006e4-104">Ruft den Namen für die Ressource von Endpunkt für den angegebenen Diensttyp ab</span><span class="sxs-lookup"><span data-stu-id="006e4-104">Gets the default endpoint resource name for the given service type</span></span>
            </summary>
        <returns><span data-ttu-id="006e4-105">Der Name der endpunktressource.</span><span class="sxs-lookup"><span data-stu-id="006e4-105">The name of the endpoint resource.</span></span></returns>
        <remarks>
          <list type="bullet">
            <item>
                    <span data-ttu-id="006e4-106">Wenn der Typname ist <code>IMyService</code>, gibt diese Methode <code>MyServiceEndpoint</code> als Namen für die Endpoint-Ressource.</span><span class="sxs-lookup"><span data-stu-id="006e4-106">If the type name is <code>IMyService</code>, this method returns <code>MyServiceEndpoint</code> as the name of the endpoint resource.</span></span>
                </item>
            <item>
                    <span data-ttu-id="006e4-107">Wenn der Typname ist <code>Foo</code>, gibt diese Methode <code>FooServiceEndpoint</code> als Namen für die Endpoint-Ressource.</span><span class="sxs-lookup"><span data-stu-id="006e4-107">If the type name is <code>Foo</code>, this method returns <code>FooServiceEndpoint</code> as the name of the endpoint resource.</span></span>
                </item>
          </list>
        </remarks>
      </Docs>
    </Member>
  </Members>
</Type>