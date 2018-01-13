<Type Name="GraphRbacManagementClient" FullName="Microsoft.Azure.Management.Graph.RBAC.Fluent.GraphRbacManagementClient">
  <TypeSignature Language="C#" Value="public class GraphRbacManagementClient : Microsoft.Rest.ServiceClient&lt;Microsoft.Azure.Management.Graph.RBAC.Fluent.GraphRbacManagementClient&gt;, IDisposable, Microsoft.Azure.Management.Graph.RBAC.Fluent.IGraphRbacManagementClient, Microsoft.Rest.Azure.IAzureClient" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit GraphRbacManagementClient extends Microsoft.Rest.ServiceClient`1&lt;class Microsoft.Azure.Management.Graph.RBAC.Fluent.GraphRbacManagementClient&gt; implements class Microsoft.Azure.Management.Graph.RBAC.Fluent.IGraphRbacManagementClient, class Microsoft.Rest.Azure.IAzureClient, class System.IDisposable" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Graph.RBAC.Fluent.GraphRbacManagementClient" />
  <TypeSignature Language="VB.NET" Value="Public Class GraphRbacManagementClient&#xA;Inherits ServiceClient(Of GraphRbacManagementClient)&#xA;Implements IAzureClient, IDisposable, IGraphRbacManagementClient" />
  <TypeSignature Language="F#" Value="type GraphRbacManagementClient = class&#xA;    inherit ServiceClient&lt;GraphRbacManagementClient&gt;&#xA;    interface IGraphRbacManagementClient&#xA;    interface IDisposable&#xA;    interface IAzureClient" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Graph.RBAC.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Rest.ServiceClient&lt;Microsoft.Azure.Management.Graph.RBAC.Fluent.GraphRbacManagementClient&gt;</BaseTypeName>
    <BaseTypeArguments>
      <BaseTypeArgument TypeParamName="!0">Microsoft.Azure.Management.Graph.RBAC.Fluent.GraphRbacManagementClient</BaseTypeArgument>
    </BaseTypeArguments>
  </Base>
  <Interfaces>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.Graph.RBAC.Fluent.IGraphRbacManagementClient</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Rest.Azure.IAzureClient</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>System.IDisposable</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <summary>
            Graph-Client für die Verwaltung der RBAC
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="protected GraphRbacManagementClient (params System.Net.Http.DelegatingHandler[] handlers);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig specialname rtspecialname instance void .ctor(class System.Net.Http.DelegatingHandler[] handlers) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Graph.RBAC.Fluent.GraphRbacManagementClient.#ctor(System.Net.Http.DelegatingHandler[])" />
      <MemberSignature Language="VB.NET" Value="Protected Sub New (ParamArray handlers As DelegatingHandler())" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Graph.RBAC.Fluent.GraphRbacManagementClient : System.Net.Http.DelegatingHandler[] -&gt; Microsoft.Azure.Management.Graph.RBAC.Fluent.GraphRbacManagementClient" Usage="new Microsoft.Azure.Management.Graph.RBAC.Fluent.GraphRbacManagementClient handlers" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Graph.RBAC.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="handlers" Type="System.Net.Http.DelegatingHandler[]">
          <Attributes>
            <Attribute>
              <AttributeName>System.ParamArray</AttributeName>
            </Attribute>
          </Attributes>
        </Parameter>
      </Parameters>
      <Docs>
        <param name="handlers">
            Optional. Die delegierenden Handler der HTTP-Client-Pipeline hinzu.
            </param>
        <summary>
            Initialisiert eine neue Instanz der GraphRbacManagementClient-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public GraphRbacManagementClient (Microsoft.Rest.ServiceClientCredentials credentials, params System.Net.Http.DelegatingHandler[] handlers);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class Microsoft.Rest.ServiceClientCredentials credentials, class System.Net.Http.DelegatingHandler[] handlers) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Graph.RBAC.Fluent.GraphRbacManagementClient.#ctor(Microsoft.Rest.ServiceClientCredentials,System.Net.Http.DelegatingHandler[])" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (credentials As ServiceClientCredentials, ParamArray handlers As DelegatingHandler())" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Graph.RBAC.Fluent.GraphRbacManagementClient : Microsoft.Rest.ServiceClientCredentials * System.Net.Http.DelegatingHandler[] -&gt; Microsoft.Azure.Management.Graph.RBAC.Fluent.GraphRbacManagementClient" Usage="new Microsoft.Azure.Management.Graph.RBAC.Fluent.GraphRbacManagementClient (credentials, handlers)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Graph.RBAC.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="credentials" Type="Microsoft.Rest.ServiceClientCredentials" />
        <Parameter Name="handlers" Type="System.Net.Http.DelegatingHandler[]">
          <Attributes>
            <Attribute>
              <AttributeName>System.ParamArray</AttributeName>
            </Attribute>
          </Attributes>
        </Parameter>
      </Parameters>
      <Docs>
        <param name="credentials">
            Erforderlich. Anmeldeinformationen für den Client zum Verbinden mit Azure erforderlich.
            </param>
        <param name="handlers">
            Optional. Die delegierenden Handler der HTTP-Client-Pipeline hinzu.
            </param>
        <summary>
            Initialisiert eine neue Instanz der GraphRbacManagementClient-Klasse.
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentNullException">
            Wird ausgelöst, wenn ein erforderlicher Parameter null ist.
            </exception>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="protected GraphRbacManagementClient (System.Net.Http.HttpClientHandler rootHandler, params System.Net.Http.DelegatingHandler[] handlers);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig specialname rtspecialname instance void .ctor(class System.Net.Http.HttpClientHandler rootHandler, class System.Net.Http.DelegatingHandler[] handlers) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Graph.RBAC.Fluent.GraphRbacManagementClient.#ctor(System.Net.Http.HttpClientHandler,System.Net.Http.DelegatingHandler[])" />
      <MemberSignature Language="VB.NET" Value="Protected Sub New (rootHandler As HttpClientHandler, ParamArray handlers As DelegatingHandler())" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Graph.RBAC.Fluent.GraphRbacManagementClient : System.Net.Http.HttpClientHandler * System.Net.Http.DelegatingHandler[] -&gt; Microsoft.Azure.Management.Graph.RBAC.Fluent.GraphRbacManagementClient" Usage="new Microsoft.Azure.Management.Graph.RBAC.Fluent.GraphRbacManagementClient (rootHandler, handlers)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Graph.RBAC.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="rootHandler" Type="System.Net.Http.HttpClientHandler" />
        <Parameter Name="handlers" Type="System.Net.Http.DelegatingHandler[]">
          <Attributes>
            <Attribute>
              <AttributeName>System.ParamArray</AttributeName>
            </Attribute>
          </Attributes>
        </Parameter>
      </Parameters>
      <Docs>
        <param name="rootHandler">
            Optional. Der Client HTTP-Handler zum Verarbeiten von HTTP-Transport verwendet.
            </param>
        <param name="handlers">
            Optional. Die delegierenden Handler der HTTP-Client-Pipeline hinzu.
            </param>
        <summary>
            Initialisiert eine neue Instanz der GraphRbacManagementClient-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="protected GraphRbacManagementClient (Uri baseUri, params System.Net.Http.DelegatingHandler[] handlers);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig specialname rtspecialname instance void .ctor(class System.Uri baseUri, class System.Net.Http.DelegatingHandler[] handlers) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Graph.RBAC.Fluent.GraphRbacManagementClient.#ctor(System.Uri,System.Net.Http.DelegatingHandler[])" />
      <MemberSignature Language="VB.NET" Value="Protected Sub New (baseUri As Uri, ParamArray handlers As DelegatingHandler())" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Graph.RBAC.Fluent.GraphRbacManagementClient : Uri * System.Net.Http.DelegatingHandler[] -&gt; Microsoft.Azure.Management.Graph.RBAC.Fluent.GraphRbacManagementClient" Usage="new Microsoft.Azure.Management.Graph.RBAC.Fluent.GraphRbacManagementClient (baseUri, handlers)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Graph.RBAC.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="baseUri" Type="System.Uri" />
        <Parameter Name="handlers" Type="System.Net.Http.DelegatingHandler[]">
          <Attributes>
            <Attribute>
              <AttributeName>System.ParamArray</AttributeName>
            </Attribute>
          </Attributes>
        </Parameter>
      </Parameters>
      <Docs>
        <param name="baseUri">
            Optional. Die Basis-URI des Diensts.
            </param>
        <param name="handlers">
            Optional. Die delegierenden Handler der HTTP-Client-Pipeline hinzu.
            </param>
        <summary>
            Initialisiert eine neue Instanz der GraphRbacManagementClient-Klasse.
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentNullException">
            Wird ausgelöst, wenn ein erforderlicher Parameter null ist.
            </exception>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public GraphRbacManagementClient (Microsoft.Rest.ServiceClientCredentials credentials, System.Net.Http.HttpClientHandler rootHandler, params System.Net.Http.DelegatingHandler[] handlers);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class Microsoft.Rest.ServiceClientCredentials credentials, class System.Net.Http.HttpClientHandler rootHandler, class System.Net.Http.DelegatingHandler[] handlers) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Graph.RBAC.Fluent.GraphRbacManagementClient.#ctor(Microsoft.Rest.ServiceClientCredentials,System.Net.Http.HttpClientHandler,System.Net.Http.DelegatingHandler[])" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (credentials As ServiceClientCredentials, rootHandler As HttpClientHandler, ParamArray handlers As DelegatingHandler())" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Graph.RBAC.Fluent.GraphRbacManagementClient : Microsoft.Rest.ServiceClientCredentials * System.Net.Http.HttpClientHandler * System.Net.Http.DelegatingHandler[] -&gt; Microsoft.Azure.Management.Graph.RBAC.Fluent.GraphRbacManagementClient" Usage="new Microsoft.Azure.Management.Graph.RBAC.Fluent.GraphRbacManagementClient (credentials, rootHandler, handlers)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Graph.RBAC.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="credentials" Type="Microsoft.Rest.ServiceClientCredentials" />
        <Parameter Name="rootHandler" Type="System.Net.Http.HttpClientHandler" />
        <Parameter Name="handlers" Type="System.Net.Http.DelegatingHandler[]">
          <Attributes>
            <Attribute>
              <AttributeName>System.ParamArray</AttributeName>
            </Attribute>
          </Attributes>
        </Parameter>
      </Parameters>
      <Docs>
        <param name="credentials">
            Erforderlich. Anmeldeinformationen für den Client zum Verbinden mit Azure erforderlich.
            </param>
        <param name="rootHandler">
            Optional. Der Client HTTP-Handler zum Verarbeiten von HTTP-Transport verwendet.
            </param>
        <param name="handlers">
            Optional. Die delegierenden Handler der HTTP-Client-Pipeline hinzu.
            </param>
        <summary>
            Initialisiert eine neue Instanz der GraphRbacManagementClient-Klasse.
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentNullException">
            Wird ausgelöst, wenn ein erforderlicher Parameter null ist.
            </exception>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public GraphRbacManagementClient (Uri baseUri, Microsoft.Rest.ServiceClientCredentials credentials, params System.Net.Http.DelegatingHandler[] handlers);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Uri baseUri, class Microsoft.Rest.ServiceClientCredentials credentials, class System.Net.Http.DelegatingHandler[] handlers) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Graph.RBAC.Fluent.GraphRbacManagementClient.#ctor(System.Uri,Microsoft.Rest.ServiceClientCredentials,System.Net.Http.DelegatingHandler[])" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (baseUri As Uri, credentials As ServiceClientCredentials, ParamArray handlers As DelegatingHandler())" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Graph.RBAC.Fluent.GraphRbacManagementClient : Uri * Microsoft.Rest.ServiceClientCredentials * System.Net.Http.DelegatingHandler[] -&gt; Microsoft.Azure.Management.Graph.RBAC.Fluent.GraphRbacManagementClient" Usage="new Microsoft.Azure.Management.Graph.RBAC.Fluent.GraphRbacManagementClient (baseUri, credentials, handlers)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Graph.RBAC.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="baseUri" Type="System.Uri" />
        <Parameter Name="credentials" Type="Microsoft.Rest.ServiceClientCredentials" />
        <Parameter Name="handlers" Type="System.Net.Http.DelegatingHandler[]">
          <Attributes>
            <Attribute>
              <AttributeName>System.ParamArray</AttributeName>
            </Attribute>
          </Attributes>
        </Parameter>
      </Parameters>
      <Docs>
        <param name="baseUri">
            Optional. Die Basis-URI des Diensts.
            </param>
        <param name="credentials">
            Erforderlich. Anmeldeinformationen für den Client zum Verbinden mit Azure erforderlich.
            </param>
        <param name="handlers">
            Optional. Die delegierenden Handler der HTTP-Client-Pipeline hinzu.
            </param>
        <summary>
            Initialisiert eine neue Instanz der GraphRbacManagementClient-Klasse.
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentNullException">
            Wird ausgelöst, wenn ein erforderlicher Parameter null ist.
            </exception>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="protected GraphRbacManagementClient (Uri baseUri, System.Net.Http.HttpClientHandler rootHandler, params System.Net.Http.DelegatingHandler[] handlers);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig specialname rtspecialname instance void .ctor(class System.Uri baseUri, class System.Net.Http.HttpClientHandler rootHandler, class System.Net.Http.DelegatingHandler[] handlers) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Graph.RBAC.Fluent.GraphRbacManagementClient.#ctor(System.Uri,System.Net.Http.HttpClientHandler,System.Net.Http.DelegatingHandler[])" />
      <MemberSignature Language="VB.NET" Value="Protected Sub New (baseUri As Uri, rootHandler As HttpClientHandler, ParamArray handlers As DelegatingHandler())" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Graph.RBAC.Fluent.GraphRbacManagementClient : Uri * System.Net.Http.HttpClientHandler * System.Net.Http.DelegatingHandler[] -&gt; Microsoft.Azure.Management.Graph.RBAC.Fluent.GraphRbacManagementClient" Usage="new Microsoft.Azure.Management.Graph.RBAC.Fluent.GraphRbacManagementClient (baseUri, rootHandler, handlers)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Graph.RBAC.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="baseUri" Type="System.Uri" />
        <Parameter Name="rootHandler" Type="System.Net.Http.HttpClientHandler" />
        <Parameter Name="handlers" Type="System.Net.Http.DelegatingHandler[]">
          <Attributes>
            <Attribute>
              <AttributeName>System.ParamArray</AttributeName>
            </Attribute>
          </Attributes>
        </Parameter>
      </Parameters>
      <Docs>
        <param name="baseUri">
            Optional. Die Basis-URI des Diensts.
            </param>
        <param name="rootHandler">
            Optional. Der Client HTTP-Handler zum Verarbeiten von HTTP-Transport verwendet.
            </param>
        <param name="handlers">
            Optional. Die delegierenden Handler der HTTP-Client-Pipeline hinzu.
            </param>
        <summary>
            Initialisiert eine neue Instanz der GraphRbacManagementClient-Klasse.
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentNullException">
            Wird ausgelöst, wenn ein erforderlicher Parameter null ist.
            </exception>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public GraphRbacManagementClient (Uri baseUri, Microsoft.Rest.ServiceClientCredentials credentials, System.Net.Http.HttpClientHandler rootHandler, params System.Net.Http.DelegatingHandler[] handlers);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Uri baseUri, class Microsoft.Rest.ServiceClientCredentials credentials, class System.Net.Http.HttpClientHandler rootHandler, class System.Net.Http.DelegatingHandler[] handlers) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Graph.RBAC.Fluent.GraphRbacManagementClient.#ctor(System.Uri,Microsoft.Rest.ServiceClientCredentials,System.Net.Http.HttpClientHandler,System.Net.Http.DelegatingHandler[])" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (baseUri As Uri, credentials As ServiceClientCredentials, rootHandler As HttpClientHandler, ParamArray handlers As DelegatingHandler())" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Graph.RBAC.Fluent.GraphRbacManagementClient : Uri * Microsoft.Rest.ServiceClientCredentials * System.Net.Http.HttpClientHandler * System.Net.Http.DelegatingHandler[] -&gt; Microsoft.Azure.Management.Graph.RBAC.Fluent.GraphRbacManagementClient" Usage="new Microsoft.Azure.Management.Graph.RBAC.Fluent.GraphRbacManagementClient (baseUri, credentials, rootHandler, handlers)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Graph.RBAC.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="baseUri" Type="System.Uri" />
        <Parameter Name="credentials" Type="Microsoft.Rest.ServiceClientCredentials" />
        <Parameter Name="rootHandler" Type="System.Net.Http.HttpClientHandler" />
        <Parameter Name="handlers" Type="System.Net.Http.DelegatingHandler[]">
          <Attributes>
            <Attribute>
              <AttributeName>System.ParamArray</AttributeName>
            </Attribute>
          </Attributes>
        </Parameter>
      </Parameters>
      <Docs>
        <param name="baseUri">
            Optional. Die Basis-URI des Diensts.
            </param>
        <param name="credentials">
            Erforderlich. Anmeldeinformationen für den Client zum Verbinden mit Azure erforderlich.
            </param>
        <param name="rootHandler">
            Optional. Der Client HTTP-Handler zum Verarbeiten von HTTP-Transport verwendet.
            </param>
        <param name="handlers">
            Optional. Die delegierenden Handler der HTTP-Client-Pipeline hinzu.
            </param>
        <summary>
            Initialisiert eine neue Instanz der GraphRbacManagementClient-Klasse.
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentNullException">
            Wird ausgelöst, wenn ein erforderlicher Parameter null ist.
            </exception>
      </Docs>
    </Member>
    <Member MemberName="AcceptLanguage">
      <MemberSignature Language="C#" Value="public string AcceptLanguage { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string AcceptLanguage" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Graph.RBAC.Fluent.GraphRbacManagementClient.AcceptLanguage" />
      <MemberSignature Language="VB.NET" Value="Public Property AcceptLanguage As String" />
      <MemberSignature Language="F#" Value="member this.AcceptLanguage : string with get, set" Usage="Microsoft.Azure.Management.Graph.RBAC.Fluent.GraphRbacManagementClient.AcceptLanguage" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.Azure.Management.Graph.RBAC.Fluent.IGraphRbacManagementClient.AcceptLanguage</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Graph.RBAC.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt die bevorzugte Sprache für die Antwort.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ApiVersion">
      <MemberSignature Language="C#" Value="public string ApiVersion { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ApiVersion" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Graph.RBAC.Fluent.GraphRbacManagementClient.ApiVersion" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ApiVersion As String" />
      <MemberSignature Language="F#" Value="member this.ApiVersion : string" Usage="Microsoft.Azure.Management.Graph.RBAC.Fluent.GraphRbacManagementClient.ApiVersion" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Graph.RBAC.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Client-API-Version.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Applications">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Graph.RBAC.Fluent.IApplicationsOperations Applications { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Graph.RBAC.Fluent.IApplicationsOperations Applications" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Graph.RBAC.Fluent.GraphRbacManagementClient.Applications" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Applications As IApplicationsOperations" />
      <MemberSignature Language="F#" Value="member this.Applications : Microsoft.Azure.Management.Graph.RBAC.Fluent.IApplicationsOperations" Usage="Microsoft.Azure.Management.Graph.RBAC.Fluent.GraphRbacManagementClient.Applications" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Graph.RBAC.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Graph.RBAC.Fluent.IApplicationsOperations</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft die IApplicationsOperations ab.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BaseUri">
      <MemberSignature Language="C#" Value="public Uri BaseUri { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Uri BaseUri" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Graph.RBAC.Fluent.GraphRbacManagementClient.BaseUri" />
      <MemberSignature Language="VB.NET" Value="Public Property BaseUri As Uri" />
      <MemberSignature Language="F#" Value="member this.BaseUri : Uri with get, set" Usage="Microsoft.Azure.Management.Graph.RBAC.Fluent.GraphRbacManagementClient.BaseUri" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.Azure.Management.Graph.RBAC.Fluent.IGraphRbacManagementClient.BaseUri</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Graph.RBAC.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Uri</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Die Basis-URI des Diensts.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Credentials">
      <MemberSignature Language="C#" Value="public Microsoft.Rest.ServiceClientCredentials Credentials { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Rest.ServiceClientCredentials Credentials" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Graph.RBAC.Fluent.GraphRbacManagementClient.Credentials" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Credentials As ServiceClientCredentials" />
      <MemberSignature Language="F#" Value="member this.Credentials : Microsoft.Rest.ServiceClientCredentials" Usage="Microsoft.Azure.Management.Graph.RBAC.Fluent.GraphRbacManagementClient.Credentials" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Graph.RBAC.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.ServiceClientCredentials</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Anmeldeinformationen für den Client zum Verbinden mit Azure erforderlich.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeserializationSettings">
      <MemberSignature Language="C#" Value="public Newtonsoft.Json.JsonSerializerSettings DeserializationSettings { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Newtonsoft.Json.JsonSerializerSettings DeserializationSettings" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Graph.RBAC.Fluent.GraphRbacManagementClient.DeserializationSettings" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property DeserializationSettings As JsonSerializerSettings" />
      <MemberSignature Language="F#" Value="member this.DeserializationSettings : Newtonsoft.Json.JsonSerializerSettings" Usage="Microsoft.Azure.Management.Graph.RBAC.Fluent.GraphRbacManagementClient.DeserializationSettings" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Graph.RBAC.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Newtonsoft.Json.JsonSerializerSettings</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ermittelt oder Json-Deserialisierung Einstellungen definiert.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Domains">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Graph.RBAC.Fluent.IDomainsOperations Domains { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Graph.RBAC.Fluent.IDomainsOperations Domains" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Graph.RBAC.Fluent.GraphRbacManagementClient.Domains" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Domains As IDomainsOperations" />
      <MemberSignature Language="F#" Value="member this.Domains : Microsoft.Azure.Management.Graph.RBAC.Fluent.IDomainsOperations" Usage="Microsoft.Azure.Management.Graph.RBAC.Fluent.GraphRbacManagementClient.Domains" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Graph.RBAC.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Graph.RBAC.Fluent.IDomainsOperations</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>To be added.</summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GenerateClientRequestId">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; GenerateClientRequestId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; GenerateClientRequestId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Graph.RBAC.Fluent.GraphRbacManagementClient.GenerateClientRequestId" />
      <MemberSignature Language="VB.NET" Value="Public Property GenerateClientRequestId As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.GenerateClientRequestId : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.Azure.Management.Graph.RBAC.Fluent.GraphRbacManagementClient.GenerateClientRequestId" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.Azure.Management.Graph.RBAC.Fluent.IGraphRbacManagementClient.GenerateClientRequestId</InterfaceMember>
        <InterfaceMember>P:Microsoft.Rest.Azure.IAzureClient.GenerateClientRequestId</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Graph.RBAC.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Bei Festlegung werden auf einen eindeutigen X-ms-Client-Request-Id-Wert "true" generiert und in jeder Anforderung enthalten. Der Standardwert ist true.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Groups">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Graph.RBAC.Fluent.IGroupsOperations Groups { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Graph.RBAC.Fluent.IGroupsOperations Groups" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Graph.RBAC.Fluent.GraphRbacManagementClient.Groups" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Groups As IGroupsOperations" />
      <MemberSignature Language="F#" Value="member this.Groups : Microsoft.Azure.Management.Graph.RBAC.Fluent.IGroupsOperations" Usage="Microsoft.Azure.Management.Graph.RBAC.Fluent.GraphRbacManagementClient.Groups" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Graph.RBAC.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Graph.RBAC.Fluent.IGroupsOperations</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft die IGroupsOperations ab.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="LongRunningOperationRetryTimeout">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; LongRunningOperationRetryTimeout { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; LongRunningOperationRetryTimeout" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Graph.RBAC.Fluent.GraphRbacManagementClient.LongRunningOperationRetryTimeout" />
      <MemberSignature Language="VB.NET" Value="Public Property LongRunningOperationRetryTimeout As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.LongRunningOperationRetryTimeout : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Management.Graph.RBAC.Fluent.GraphRbacManagementClient.LongRunningOperationRetryTimeout" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.Azure.Management.Graph.RBAC.Fluent.IGraphRbacManagementClient.LongRunningOperationRetryTimeout</InterfaceMember>
        <InterfaceMember>P:Microsoft.Rest.Azure.IAzureClient.LongRunningOperationRetryTimeout</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Graph.RBAC.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt das wiederholungstimeout in Sekunden für zeitintensive Vorgänge.
            Standardwert ist 30.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Objects">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Graph.RBAC.Fluent.IObjectsOperations Objects { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Graph.RBAC.Fluent.IObjectsOperations Objects" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Graph.RBAC.Fluent.GraphRbacManagementClient.Objects" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Objects As IObjectsOperations" />
      <MemberSignature Language="F#" Value="member this.Objects : Microsoft.Azure.Management.Graph.RBAC.Fluent.IObjectsOperations" Usage="Microsoft.Azure.Management.Graph.RBAC.Fluent.GraphRbacManagementClient.Objects" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Graph.RBAC.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Graph.RBAC.Fluent.IObjectsOperations</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft die IObjectsOperations ab.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SerializationSettings">
      <MemberSignature Language="C#" Value="public Newtonsoft.Json.JsonSerializerSettings SerializationSettings { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Newtonsoft.Json.JsonSerializerSettings SerializationSettings" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Graph.RBAC.Fluent.GraphRbacManagementClient.SerializationSettings" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property SerializationSettings As JsonSerializerSettings" />
      <MemberSignature Language="F#" Value="member this.SerializationSettings : Newtonsoft.Json.JsonSerializerSettings" Usage="Microsoft.Azure.Management.Graph.RBAC.Fluent.GraphRbacManagementClient.SerializationSettings" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Graph.RBAC.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Newtonsoft.Json.JsonSerializerSettings</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ermittelt oder Json-Serialisierungseinstellungen definiert.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ServicePrincipals">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Graph.RBAC.Fluent.IServicePrincipalsOperations ServicePrincipals { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Graph.RBAC.Fluent.IServicePrincipalsOperations ServicePrincipals" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Graph.RBAC.Fluent.GraphRbacManagementClient.ServicePrincipals" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ServicePrincipals As IServicePrincipalsOperations" />
      <MemberSignature Language="F#" Value="member this.ServicePrincipals : Microsoft.Azure.Management.Graph.RBAC.Fluent.IServicePrincipalsOperations" Usage="Microsoft.Azure.Management.Graph.RBAC.Fluent.GraphRbacManagementClient.ServicePrincipals" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Graph.RBAC.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Graph.RBAC.Fluent.IServicePrincipalsOperations</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft die IServicePrincipalsOperations ab.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TenantID">
      <MemberSignature Language="C#" Value="public string TenantID { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string TenantID" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Graph.RBAC.Fluent.GraphRbacManagementClient.TenantID" />
      <MemberSignature Language="VB.NET" Value="Public Property TenantID As String" />
      <MemberSignature Language="F#" Value="member this.TenantID : string with get, set" Usage="Microsoft.Azure.Management.Graph.RBAC.Fluent.GraphRbacManagementClient.TenantID" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.Azure.Management.Graph.RBAC.Fluent.IGraphRbacManagementClient.TenantID</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Graph.RBAC.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Die Mandanten-ID.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Users">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Graph.RBAC.Fluent.IUsersOperations Users { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Graph.RBAC.Fluent.IUsersOperations Users" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Graph.RBAC.Fluent.GraphRbacManagementClient.Users" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Users As IUsersOperations" />
      <MemberSignature Language="F#" Value="member this.Users : Microsoft.Azure.Management.Graph.RBAC.Fluent.IUsersOperations" Usage="Microsoft.Azure.Management.Graph.RBAC.Fluent.GraphRbacManagementClient.Users" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Graph.RBAC.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Graph.RBAC.Fluent.IUsersOperations</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft die IUsersOperations ab.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>