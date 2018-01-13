<Type Name="XeroLinkedService" FullName="Microsoft.Azure.Management.DataFactory.Models.XeroLinkedService">
  <TypeSignature Language="C#" Value="public class XeroLinkedService : Microsoft.Azure.Management.DataFactory.Models.LinkedService" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit XeroLinkedService extends Microsoft.Azure.Management.DataFactory.Models.LinkedService" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.DataFactory.Models.XeroLinkedService" />
  <TypeSignature Language="VB.NET" Value="Public Class XeroLinkedService&#xA;Inherits LinkedService" />
  <TypeSignature Language="F#" Value="type XeroLinkedService = class&#xA;    inherit LinkedService" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
    <AssemblyVersion>0.3.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Management.DataFactory.Models.LinkedService</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>Microsoft.Rest.Serialization.JsonTransformation</AttributeName>
    </Attribute>
    <Attribute>
      <AttributeName>Newtonsoft.Json.JsonObject("Xero")</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            Xero Serivce verknüpfter Dienst.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public XeroLinkedService ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.Models.XeroLinkedService.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            Initialisiert eine neue Instanz der XeroLinkedService-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public XeroLinkedService (object host, System.Collections.Generic.IDictionary&lt;string,object&gt; additionalProperties = null, Microsoft.Azure.Management.DataFactory.Models.IntegrationRuntimeReference connectVia = null, string description = null, Microsoft.Azure.Management.DataFactory.Models.SecretBase consumerKey = null, Microsoft.Azure.Management.DataFactory.Models.SecretBase privateKey = null, object useEncryptedEndpoints = null, object useHostVerification = null, object usePeerVerification = null, object encryptedCredential = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(object host, class System.Collections.Generic.IDictionary`2&lt;string, object&gt; additionalProperties, class Microsoft.Azure.Management.DataFactory.Models.IntegrationRuntimeReference connectVia, string description, class Microsoft.Azure.Management.DataFactory.Models.SecretBase consumerKey, class Microsoft.Azure.Management.DataFactory.Models.SecretBase privateKey, object useEncryptedEndpoints, object useHostVerification, object usePeerVerification, object encryptedCredential) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.Models.XeroLinkedService.#ctor(System.Object,System.Collections.Generic.IDictionary{System.String,System.Object},Microsoft.Azure.Management.DataFactory.Models.IntegrationRuntimeReference,System.String,Microsoft.Azure.Management.DataFactory.Models.SecretBase,Microsoft.Azure.Management.DataFactory.Models.SecretBase,System.Object,System.Object,System.Object,System.Object)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (host As Object, Optional additionalProperties As IDictionary(Of String, Object) = null, Optional connectVia As IntegrationRuntimeReference = null, Optional description As String = null, Optional consumerKey As SecretBase = null, Optional privateKey As SecretBase = null, Optional useEncryptedEndpoints As Object = null, Optional useHostVerification As Object = null, Optional usePeerVerification As Object = null, Optional encryptedCredential As Object = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.DataFactory.Models.XeroLinkedService : obj * System.Collections.Generic.IDictionary&lt;string, obj&gt; * Microsoft.Azure.Management.DataFactory.Models.IntegrationRuntimeReference * string * Microsoft.Azure.Management.DataFactory.Models.SecretBase * Microsoft.Azure.Management.DataFactory.Models.SecretBase * obj * obj * obj * obj -&gt; Microsoft.Azure.Management.DataFactory.Models.XeroLinkedService" Usage="new Microsoft.Azure.Management.DataFactory.Models.XeroLinkedService (host, additionalProperties, connectVia, description, consumerKey, privateKey, useEncryptedEndpoints, useHostVerification, usePeerVerification, encryptedCredential)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="host" Type="System.Object" />
        <Parameter Name="additionalProperties" Type="System.Collections.Generic.IDictionary&lt;System.String,System.Object&gt;" />
        <Parameter Name="connectVia" Type="Microsoft.Azure.Management.DataFactory.Models.IntegrationRuntimeReference" />
        <Parameter Name="description" Type="System.String" />
        <Parameter Name="consumerKey" Type="Microsoft.Azure.Management.DataFactory.Models.SecretBase" />
        <Parameter Name="privateKey" Type="Microsoft.Azure.Management.DataFactory.Models.SecretBase" />
        <Parameter Name="useEncryptedEndpoints" Type="System.Object" />
        <Parameter Name="useHostVerification" Type="System.Object" />
        <Parameter Name="usePeerVerification" Type="System.Object" />
        <Parameter Name="encryptedCredential" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="host">Der Endpunkt des Xero-Servers. (d. h. api.xero.com)</param>
        <param name="additionalProperties">Nicht übereinstimmende Eigenschaften aus der Nachricht deserialisiert werden diese Sammlung</param>
        <param name="connectVia">Der Integration Common Language Runtime-Verweis.</param>
        <param name="description">Beschreibung des verknüpften Diensts.</param>
        <param name="consumerKey">Der Consumerschlüssel, der der Xero-Anwendung zugeordnet ist.</param>
        <param name="privateKey">Der private Schlüssel aus der PEM-Datei, der für Ihre private Xero-Anwendung generiert wurde. Sie müssen den gesamten Text aus der PEM-Datei, einschließlich der Unix-Zeile Zeilenenden () einschließen.</param>
        <param name="useEncryptedEndpoints">Gibt an, ob die Endpunkte der Datenquelle mit HTTPS verschlüsselt sind. Der Standardwert lautet „true“.</param>
        <param name="useHostVerification">Gibt an, ob der Hostname im Zertifikat des Servers mit dem Hostnamen des Servers übereinstimmen muss, wenn eine Verbindung über SSL hergestellt wird. Der Standardwert lautet „true“.</param>
        <param name="usePeerVerification">Gibt an, ob die Identität des Servers bei Verbindung über SSL überprüft werden soll. Der Standardwert lautet „true“.</param>
        <param name="encryptedCredential">Die verschlüsselten Anmeldeinformationen für die Authentifizierung verwendet. Anmeldeinformationen werden verschlüsselt, mit dem Integration Runtime Anmeldeinformations-Manager. Typ: Zeichenfolge (oder Ausdruck mit ResultType-Zeichenfolge).</param>
        <summary>
            Initialisiert eine neue Instanz der XeroLinkedService-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ConsumerKey">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.DataFactory.Models.SecretBase ConsumerKey { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.DataFactory.Models.SecretBase ConsumerKey" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.XeroLinkedService.ConsumerKey" />
      <MemberSignature Language="VB.NET" Value="Public Property ConsumerKey As SecretBase" />
      <MemberSignature Language="F#" Value="member this.ConsumerKey : Microsoft.Azure.Management.DataFactory.Models.SecretBase with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.XeroLinkedService.ConsumerKey" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="typeProperties.consumerKey")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.DataFactory.Models.SecretBase</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab, oder legt ihn fest der Verbraucherschlüssel, der Xero-Anwendung zugeordnet.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EncryptedCredential">
      <MemberSignature Language="C#" Value="public object EncryptedCredential { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance object EncryptedCredential" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.XeroLinkedService.EncryptedCredential" />
      <MemberSignature Language="VB.NET" Value="Public Property EncryptedCredential As Object" />
      <MemberSignature Language="F#" Value="member this.EncryptedCredential : obj with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.XeroLinkedService.EncryptedCredential" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="typeProperties.encryptedCredential")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Object</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt die verschlüsselte Anmeldeinformationen für die Authentifizierung verwendet.
            Anmeldeinformationen werden verschlüsselt, mit dem Integration Runtime Anmeldeinformations-Manager. Typ: Zeichenfolge (oder Ausdruck mit ResultType-Zeichenfolge).
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Host">
      <MemberSignature Language="C#" Value="public object Host { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance object Host" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.XeroLinkedService.Host" />
      <MemberSignature Language="VB.NET" Value="Public Property Host As Object" />
      <MemberSignature Language="F#" Value="member this.Host : obj with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.XeroLinkedService.Host" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="typeProperties.host")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Object</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt den Endpunkt des Servers Xero. (d. h. api.xero.com)
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PrivateKey">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.DataFactory.Models.SecretBase PrivateKey { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.DataFactory.Models.SecretBase PrivateKey" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.XeroLinkedService.PrivateKey" />
      <MemberSignature Language="VB.NET" Value="Public Property PrivateKey As SecretBase" />
      <MemberSignature Language="F#" Value="member this.PrivateKey : Microsoft.Azure.Management.DataFactory.Models.SecretBase with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.XeroLinkedService.PrivateKey" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="typeProperties.privateKey")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.DataFactory.Models.SecretBase</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt den privaten Schlüssel aus der PEM-Datei, die generiert wurde, für Ihre private Xero-Anwendung. Sie müssen den gesamten Text aus der PEM-Datei, einschließlich der Unix-Zeile Zeilenenden () einschließen.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UseEncryptedEndpoints">
      <MemberSignature Language="C#" Value="public object UseEncryptedEndpoints { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance object UseEncryptedEndpoints" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.XeroLinkedService.UseEncryptedEndpoints" />
      <MemberSignature Language="VB.NET" Value="Public Property UseEncryptedEndpoints As Object" />
      <MemberSignature Language="F#" Value="member this.UseEncryptedEndpoints : obj with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.XeroLinkedService.UseEncryptedEndpoints" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="typeProperties.useEncryptedEndpoints")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Object</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Gibt an, ob die Quelle Datenendpunkte über HTTPS verschlüsselt werden, ruft ab oder legt ihn fest. Der Standardwert lautet „true“.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UseHostVerification">
      <MemberSignature Language="C#" Value="public object UseHostVerification { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance object UseHostVerification" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.XeroLinkedService.UseHostVerification" />
      <MemberSignature Language="VB.NET" Value="Public Property UseHostVerification As Object" />
      <MemberSignature Language="F#" Value="member this.UseHostVerification : obj with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.XeroLinkedService.UseHostVerification" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="typeProperties.useHostVerification")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Object</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Gibt an, ob der Hostname im Zertifikat des Servers, den Hostnamen des Servers entsprechend der Verbindungsaufbau über SSL erforderlich ist, ruft ab oder legt ihn fest. Der Standardwert lautet „true“.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UsePeerVerification">
      <MemberSignature Language="C#" Value="public object UsePeerVerification { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance object UsePeerVerification" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.XeroLinkedService.UsePeerVerification" />
      <MemberSignature Language="VB.NET" Value="Public Property UsePeerVerification As Object" />
      <MemberSignature Language="F#" Value="member this.UsePeerVerification : obj with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.XeroLinkedService.UsePeerVerification" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="typeProperties.usePeerVerification")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Object</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Gibt an, ob die Identität des Servers zu überprüfen, Verbindungsaufbau über SSL, ruft ab oder legt ihn fest. Der Standardwert lautet „true“.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public override void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.Models.XeroLinkedService.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Sub Validate ()" />
      <MemberSignature Language="F#" Value="override this.Validate : unit -&gt; unit" Usage="xeroLinkedService.Validate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            Überprüfen Sie das Objekt.
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            Wird ausgelöst, wenn die Validierung fehlschlägt
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>