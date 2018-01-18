<Type Name="WebListenerCommunicationListener" FullName="Microsoft.ServiceFabric.Services.Communication.AspNetCore.WebListenerCommunicationListener">
  <TypeSignature Language="C#" Value="public class WebListenerCommunicationListener : Microsoft.ServiceFabric.Services.Communication.AspNetCore.AspNetCoreCommunicationListener" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit WebListenerCommunicationListener extends Microsoft.ServiceFabric.Services.Communication.AspNetCore.AspNetCoreCommunicationListener" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceFabric.Services.Communication.AspNetCore.WebListenerCommunicationListener" />
  <TypeSignature Language="VB.NET" Value="Public Class WebListenerCommunicationListener&#xA;Inherits AspNetCoreCommunicationListener" />
  <TypeSignature Language="F#" Value="type WebListenerCommunicationListener = class&#xA;    inherit AspNetCoreCommunicationListener" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.ServiceFabric.AspNetCore.WebListener</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.ServiceFabric.Services.Communication.AspNetCore.AspNetCoreCommunicationListener</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="27219-101">Ein AspNetCore WebListener basierte Kommunikation Listener für zustandslose oder zustandsbehaftete Service Fabric-Dienst.</span><span class="sxs-lookup"><span data-stu-id="27219-101">An AspNetCore WebListener based communication listener for Service Fabric stateless or stateful service.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public WebListenerCommunicationListener (System.Fabric.ServiceContext serviceContext, string endpointName, Func&lt;string,Microsoft.ServiceFabric.Services.Communication.AspNetCore.AspNetCoreCommunicationListener,Microsoft.AspNetCore.Hosting.IWebHost&gt; build);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Fabric.ServiceContext serviceContext, string endpointName, class System.Func`3&lt;string, class Microsoft.ServiceFabric.Services.Communication.AspNetCore.AspNetCoreCommunicationListener, class Microsoft.AspNetCore.Hosting.IWebHost&gt; build) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Services.Communication.AspNetCore.WebListenerCommunicationListener.#ctor(System.Fabric.ServiceContext,System.String,System.Func{System.String,Microsoft.ServiceFabric.Services.Communication.AspNetCore.AspNetCoreCommunicationListener,Microsoft.AspNetCore.Hosting.IWebHost})" />
      <MemberSignature Language="F#" Value="new Microsoft.ServiceFabric.Services.Communication.AspNetCore.WebListenerCommunicationListener : System.Fabric.ServiceContext * string * Func&lt;string, Microsoft.ServiceFabric.Services.Communication.AspNetCore.AspNetCoreCommunicationListener, Microsoft.AspNetCore.Hosting.IWebHost&gt; -&gt; Microsoft.ServiceFabric.Services.Communication.AspNetCore.WebListenerCommunicationListener" Usage="new Microsoft.ServiceFabric.Services.Communication.AspNetCore.WebListenerCommunicationListener (serviceContext, endpointName, build)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.AspNetCore.WebListener</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="serviceContext" Type="System.Fabric.ServiceContext" />
        <Parameter Name="endpointName" Type="System.String" />
        <Parameter Name="build" Type="System.Func&lt;System.String,Microsoft.ServiceFabric.Services.Communication.AspNetCore.AspNetCoreCommunicationListener,Microsoft.AspNetCore.Hosting.IWebHost&gt;" />
      </Parameters>
      <Docs>
        <param name="serviceContext"><span data-ttu-id="27219-102">Der Kontext des Diensts für die Kommunikation Listener erstellt wird.</span><span class="sxs-lookup"><span data-stu-id="27219-102">The context of the service for which this communication listener is being constructed.</span></span></param>
        <param name="endpointName"><span data-ttu-id="27219-103">Name des endpunktressource definiert im Dienstmanifest, die verwendet werden soll, um die Adresse für den Listener zu erstellen.</span><span class="sxs-lookup"><span data-stu-id="27219-103">Name of endpoint resource defined in service manifest that should be used to create the address for listener.</span></span></param>
        <param name="build"><span data-ttu-id="27219-104">Delegieren zum Erstellen von Microsoft.AspNetCore.Hosting.IWebHost, Endpunkt-Url, die vom Listener generiert erhält als Eingabe für dieses Delegaten.</span><span class="sxs-lookup"><span data-stu-id="27219-104">Delegate to build Microsoft.AspNetCore.Hosting.IWebHost, endpoint url generated by the listener is given as input to this delegate.</span></span>
            <span data-ttu-id="27219-105">Dies bietet die Flexibilität, die Url vor dem Erstellen von Microsoft.AspNetCore.Hosting.IWebHost bei Bedarf zu ändern.</span><span class="sxs-lookup"><span data-stu-id="27219-105">This gives the flexibility to change the url before creating Microsoft.AspNetCore.Hosting.IWebHost if needed.</span></span></param>
        <summary>
            <span data-ttu-id="27219-106">Erstellt eine AspNetCore WebListener basierend Kommunikation Listener.</span><span class="sxs-lookup"><span data-stu-id="27219-106">Constructs a AspNetCore WebListener based communication listener.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetListenerUrl">
      <MemberSignature Language="C#" Value="protected override string GetListenerUrl ();" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig virtual instance string GetListenerUrl() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Services.Communication.AspNetCore.WebListenerCommunicationListener.GetListenerUrl" />
      <MemberSignature Language="VB.NET" Value="Protected Overrides Function GetListenerUrl () As String" />
      <MemberSignature Language="F#" Value="override this.GetListenerUrl : unit -&gt; string" Usage="webListenerCommunicationListener.GetListenerUrl " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.AspNetCore.WebListener</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="27219-107">Ruft die Url für den Listener ab.</span><span class="sxs-lookup"><span data-stu-id="27219-107">Gets url for the listener.</span></span> <span data-ttu-id="27219-108">Listener-Url wird erstellt, mit den Filtern EndpointName, die in den Konstruktor übergeben.</span><span class="sxs-lookup"><span data-stu-id="27219-108">Listener url is created using the endpointName passed in the constructor.</span></span>
            </summary>
        <returns><span data-ttu-id="27219-109">die URL für den Listener.</span><span class="sxs-lookup"><span data-stu-id="27219-109">url for the listener.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>