<Type Name="ExpressRouteCircuitAuthorizationInner" FullName="Microsoft.Azure.Management.Network.Fluent.Models.ExpressRouteCircuitAuthorizationInner">
  <TypeSignature Language="C#" Value="public class ExpressRouteCircuitAuthorizationInner : Microsoft.Azure.Management.ResourceManager.Fluent.SubResource" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit ExpressRouteCircuitAuthorizationInner extends Microsoft.Azure.Management.ResourceManager.Fluent.SubResource" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Network.Fluent.Models.ExpressRouteCircuitAuthorizationInner" />
  <TypeSignature Language="VB.NET" Value="Public Class ExpressRouteCircuitAuthorizationInner&#xA;Inherits SubResource" />
  <TypeSignature Language="F#" Value="type ExpressRouteCircuitAuthorizationInner = class&#xA;    inherit SubResource" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Management.ResourceManager.Fluent.SubResource</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>Microsoft.Rest.Serialization.JsonTransformation</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            Autorisierung in einer ExpressRouteCircuit-Ressource.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ExpressRouteCircuitAuthorizationInner ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.Models.ExpressRouteCircuitAuthorizationInner.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            Initialisiert eine neue Instanz der ExpressRouteCircuitAuthorizationInner-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ExpressRouteCircuitAuthorizationInner (string id = null, string authorizationKey = null, string authorizationUseStatus = null, string provisioningState = null, string name = null, string etag = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string id, string authorizationKey, string authorizationUseStatus, string provisioningState, string name, string etag) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.Models.ExpressRouteCircuitAuthorizationInner.#ctor(System.String,System.String,System.String,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional id As String = null, Optional authorizationKey As String = null, Optional authorizationUseStatus As String = null, Optional provisioningState As String = null, Optional name As String = null, Optional etag As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Network.Fluent.Models.ExpressRouteCircuitAuthorizationInner : string * string * string * string * string * string -&gt; Microsoft.Azure.Management.Network.Fluent.Models.ExpressRouteCircuitAuthorizationInner" Usage="new Microsoft.Azure.Management.Network.Fluent.Models.ExpressRouteCircuitAuthorizationInner (id, authorizationKey, authorizationUseStatus, provisioningState, name, etag)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="id" Type="System.String" />
        <Parameter Name="authorizationKey" Type="System.String" />
        <Parameter Name="authorizationUseStatus" Type="System.String" />
        <Parameter Name="provisioningState" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="etag" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="id">To be added.</param>
        <param name="authorizationKey">Der Schlüssel für die Autorisierung.</param>
        <param name="authorizationUseStatus">AuthorizationUseStatus.
            Mögliche Werte sind: "Verfügbar" und "InUse". Folgende Werte sind möglich: "Verfügbar", "InUse"</param>
        <param name="provisioningState">Ruft den Bereitstellungsstatus der öffentlichen IP-Ressource ab. Mögliche Werte sind: "Aktualisieren", "Löschen" und "Fehler".</param>
        <param name="name">Ruft die Namen der Ressource, die innerhalb einer Ressourcengruppe eindeutig ist. Dieser Name kann verwendet werden, auf die Ressource zuzugreifen.</param>
        <param name="etag">Eine eindeutige schreibgeschützte Zeichenfolge, die geändert werden, wenn die Ressource aktualisiert wird.</param>
        <summary>
            Initialisiert eine neue Instanz der ExpressRouteCircuitAuthorizationInner-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AuthorizationKey">
      <MemberSignature Language="C#" Value="public string AuthorizationKey { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string AuthorizationKey" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Fluent.Models.ExpressRouteCircuitAuthorizationInner.AuthorizationKey" />
      <MemberSignature Language="VB.NET" Value="Public Property AuthorizationKey As String" />
      <MemberSignature Language="F#" Value="member this.AuthorizationKey : string with get, set" Usage="Microsoft.Azure.Management.Network.Fluent.Models.ExpressRouteCircuitAuthorizationInner.AuthorizationKey" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.authorizationKey")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt den Schlüssel für die Autorisierung.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AuthorizationUseStatus">
      <MemberSignature Language="C#" Value="public string AuthorizationUseStatus { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string AuthorizationUseStatus" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Fluent.Models.ExpressRouteCircuitAuthorizationInner.AuthorizationUseStatus" />
      <MemberSignature Language="VB.NET" Value="Public Property AuthorizationUseStatus As String" />
      <MemberSignature Language="F#" Value="member this.AuthorizationUseStatus : string with get, set" Usage="Microsoft.Azure.Management.Network.Fluent.Models.ExpressRouteCircuitAuthorizationInner.AuthorizationUseStatus" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.authorizationUseStatus")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt die AuthorizationUseStatus fest. Mögliche Werte sind: "Verfügbar" und "InUse". Folgende Werte sind möglich: "Verfügbar", "InUse"
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Etag">
      <MemberSignature Language="C#" Value="public string Etag { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Etag" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Fluent.Models.ExpressRouteCircuitAuthorizationInner.Etag" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Etag As String" />
      <MemberSignature Language="F#" Value="member this.Etag : string" Usage="Microsoft.Azure.Management.Network.Fluent.Models.ExpressRouteCircuitAuthorizationInner.Etag" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="etag")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft eine eindeutige Zeichenfolge ohne Schreibzugriff, die geändert werden, wenn die Ressource aktualisiert wird.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Name">
      <MemberSignature Language="C#" Value="public string Name { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Name" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Fluent.Models.ExpressRouteCircuitAuthorizationInner.Name" />
      <MemberSignature Language="VB.NET" Value="Public Property Name As String" />
      <MemberSignature Language="F#" Value="member this.Name : string with get, set" Usage="Microsoft.Azure.Management.Network.Fluent.Models.ExpressRouteCircuitAuthorizationInner.Name" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="name")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft die Namen der Ressource, die innerhalb einer Ressourcengruppe eindeutig ist.
            Dieser Name kann verwendet werden, auf die Ressource zuzugreifen.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ProvisioningState">
      <MemberSignature Language="C#" Value="public string ProvisioningState { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ProvisioningState" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Fluent.Models.ExpressRouteCircuitAuthorizationInner.ProvisioningState" />
      <MemberSignature Language="VB.NET" Value="Public Property ProvisioningState As String" />
      <MemberSignature Language="F#" Value="member this.ProvisioningState : string with get, set" Usage="Microsoft.Azure.Management.Network.Fluent.Models.ExpressRouteCircuitAuthorizationInner.ProvisioningState" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.provisioningState")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft den Bereitstellungsstatus der öffentlichen IP-Ressource ab. Mögliche Werte sind: "Aktualisieren", "Löschen" und "Fehler".
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>