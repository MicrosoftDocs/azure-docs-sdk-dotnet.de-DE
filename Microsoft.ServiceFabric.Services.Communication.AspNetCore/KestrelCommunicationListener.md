<Type Name="KestrelCommunicationListener" FullName="Microsoft.ServiceFabric.Services.Communication.AspNetCore.KestrelCommunicationListener">
  <TypeSignature Language="C#" Value="public class KestrelCommunicationListener : Microsoft.ServiceFabric.Services.Communication.AspNetCore.AspNetCoreCommunicationListener" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit KestrelCommunicationListener extends Microsoft.ServiceFabric.Services.Communication.AspNetCore.AspNetCoreCommunicationListener" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceFabric.Services.Communication.AspNetCore.KestrelCommunicationListener" />
  <TypeSignature Language="VB.NET" Value="Public Class KestrelCommunicationListener&#xA;Inherits AspNetCoreCommunicationListener" />
  <TypeSignature Language="F#" Value="type KestrelCommunicationListener = class&#xA;    inherit AspNetCoreCommunicationListener" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.ServiceFabric.AspNetCore.Kestrel</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.ServiceFabric.Services.Communication.AspNetCore.AspNetCoreCommunicationListener</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            Ein AspNetCore Kestrel basierte Kommunikation Listener für zustandslose oder zustandsbehaftete Service Fabric-Dienst.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public KestrelCommunicationListener (System.Fabric.ServiceContext serviceContext, Func&lt;string,Microsoft.ServiceFabric.Services.Communication.AspNetCore.AspNetCoreCommunicationListener,Microsoft.AspNetCore.Hosting.IWebHost&gt; build);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Fabric.ServiceContext serviceContext, class System.Func`3&lt;string, class Microsoft.ServiceFabric.Services.Communication.AspNetCore.AspNetCoreCommunicationListener, class Microsoft.AspNetCore.Hosting.IWebHost&gt; build) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Services.Communication.AspNetCore.KestrelCommunicationListener.#ctor(System.Fabric.ServiceContext,System.Func{System.String,Microsoft.ServiceFabric.Services.Communication.AspNetCore.AspNetCoreCommunicationListener,Microsoft.AspNetCore.Hosting.IWebHost})" />
      <MemberSignature Language="F#" Value="new Microsoft.ServiceFabric.Services.Communication.AspNetCore.KestrelCommunicationListener : System.Fabric.ServiceContext * Func&lt;string, Microsoft.ServiceFabric.Services.Communication.AspNetCore.AspNetCoreCommunicationListener, Microsoft.AspNetCore.Hosting.IWebHost&gt; -&gt; Microsoft.ServiceFabric.Services.Communication.AspNetCore.KestrelCommunicationListener" Usage="new Microsoft.ServiceFabric.Services.Communication.AspNetCore.KestrelCommunicationListener (serviceContext, build)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.AspNetCore.Kestrel</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="serviceContext" Type="System.Fabric.ServiceContext" />
        <Parameter Name="build" Type="System.Func&lt;System.String,Microsoft.ServiceFabric.Services.Communication.AspNetCore.AspNetCoreCommunicationListener,Microsoft.AspNetCore.Hosting.IWebHost&gt;" />
      </Parameters>
      <Docs>
        <param name="serviceContext">Der Kontext des Diensts für die Kommunikation Listener erstellt wird.</param>
        <param name="build">Delegieren zum Erstellen von Microsoft.AspNetCore.Hosting.IWebHost, Endpunkt-Url, die vom Listener generiert erhält als Eingabe für dieses Delegaten.
            Dies bietet die Flexibilität, die Url vor dem Erstellen von Microsoft.AspNetCore.Hosting.IWebHost bei Bedarf zu ändern.</param>
        <summary>
            Erstellt eine AspNetCore Kestrel basierend Kommunikation Listener eine Standardadresse mit HTTP-Protokoll und Port 0.
            Kestrel wird an einen Port nicht angegeben, die dynamisch binden, wenn Port 0 in der Url angegeben ist.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public KestrelCommunicationListener (System.Fabric.ServiceContext serviceContext, string endpointName, Func&lt;string,Microsoft.ServiceFabric.Services.Communication.AspNetCore.AspNetCoreCommunicationListener,Microsoft.AspNetCore.Hosting.IWebHost&gt; build);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Fabric.ServiceContext serviceContext, string endpointName, class System.Func`3&lt;string, class Microsoft.ServiceFabric.Services.Communication.AspNetCore.AspNetCoreCommunicationListener, class Microsoft.AspNetCore.Hosting.IWebHost&gt; build) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Services.Communication.AspNetCore.KestrelCommunicationListener.#ctor(System.Fabric.ServiceContext,System.String,System.Func{System.String,Microsoft.ServiceFabric.Services.Communication.AspNetCore.AspNetCoreCommunicationListener,Microsoft.AspNetCore.Hosting.IWebHost})" />
      <MemberSignature Language="F#" Value="new Microsoft.ServiceFabric.Services.Communication.AspNetCore.KestrelCommunicationListener : System.Fabric.ServiceContext * string * Func&lt;string, Microsoft.ServiceFabric.Services.Communication.AspNetCore.AspNetCoreCommunicationListener, Microsoft.AspNetCore.Hosting.IWebHost&gt; -&gt; Microsoft.ServiceFabric.Services.Communication.AspNetCore.KestrelCommunicationListener" Usage="new Microsoft.ServiceFabric.Services.Communication.AspNetCore.KestrelCommunicationListener (serviceContext, endpointName, build)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.AspNetCore.Kestrel</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="serviceContext" Type="System.Fabric.ServiceContext" />
        <Parameter Name="endpointName" Type="System.String" />
        <Parameter Name="build" Type="System.Func&lt;System.String,Microsoft.ServiceFabric.Services.Communication.AspNetCore.AspNetCoreCommunicationListener,Microsoft.AspNetCore.Hosting.IWebHost&gt;" />
      </Parameters>
      <Docs>
        <param name="serviceContext">Der Kontext des Diensts für die Kommunikation Listener erstellt wird.</param>
        <param name="endpointName">Name des endpunktressource definiert im Dienstmanifest, die verwendet werden soll, um die Adresse für den Listener zu erstellen.
            Protokoll und in diesen Endpunkt angegebenen Port wird verwendet, um die Url zu erstellen.
            Wenn die EndpointName null ist, wird eine Standardadresse mit HTTP-Protokoll und Port 0 verwendet werden.
            Kestrel wird an einen Port nicht angegeben, die dynamisch binden, wenn Port 0 in der Url angegeben ist.
            Wenn der angegebene EndpointName im Dienstmanifest nicht gefunden wird, wird eine InvalidOperationException, der angibt, das ausgelöst.</param>
        <param name="build">Delegieren zum Erstellen von Microsoft.AspNetCore.Hosting.IWebHost, Endpunkt-Url, die vom Listener generiert erhält als Eingabe für dieses Delegaten.
            Dies bietet die Flexibilität, die Url vor dem Erstellen von Microsoft.AspNetCore.Hosting.IWebHost bei Bedarf zu ändern.</param>
        <summary>
            Erstellt eine AspNetCore Kestrel basierend Kommunikation Listener.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetListenerUrl">
      <MemberSignature Language="C#" Value="protected override string GetListenerUrl ();" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig virtual instance string GetListenerUrl() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Services.Communication.AspNetCore.KestrelCommunicationListener.GetListenerUrl" />
      <MemberSignature Language="VB.NET" Value="Protected Overrides Function GetListenerUrl () As String" />
      <MemberSignature Language="F#" Value="override this.GetListenerUrl : unit -&gt; string" Usage="kestrelCommunicationListener.GetListenerUrl " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.AspNetCore.Kestrel</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            Ruft die Url für den Listener ab. Listener-Url wird erstellt, mit den Filtern EndpointName, die in den Konstruktor übergeben.
            Wenn die EndpointName null war, wird eine standardmäßige Url mit HTTP-Protokoll und Port 0 (null) zurückgegeben.
            </summary>
        <returns>die URL für den Listener.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>