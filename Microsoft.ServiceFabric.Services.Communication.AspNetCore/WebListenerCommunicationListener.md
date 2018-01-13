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
            Ein AspNetCore WebListener basierte Kommunikation Listener für zustandslose oder zustandsbehaftete Service Fabric-Dienst.
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
        <param name="serviceContext">Der Kontext des Diensts für die Kommunikation Listener erstellt wird.</param>
        <param name="endpointName">Name des endpunktressource definiert im Dienstmanifest, die verwendet werden soll, um die Adresse für den Listener zu erstellen.</param>
        <param name="build">Delegieren zum Erstellen von Microsoft.AspNetCore.Hosting.IWebHost, Endpunkt-Url, die vom Listener generiert erhält als Eingabe für dieses Delegaten.
            Dies bietet die Flexibilität, die Url vor dem Erstellen von Microsoft.AspNetCore.Hosting.IWebHost bei Bedarf zu ändern.</param>
        <summary>
            Erstellt eine AspNetCore WebListener basierend Kommunikation Listener.
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
            Ruft die Url für den Listener ab. Listener-Url wird erstellt, mit den Filtern EndpointName, die in den Konstruktor übergeben.
            </summary>
        <returns>die URL für den Listener.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>