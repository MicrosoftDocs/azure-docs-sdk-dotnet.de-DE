<Type Name="AmazonMWSLinkedService" FullName="Microsoft.Azure.Management.DataFactory.Models.AmazonMWSLinkedService">
  <TypeSignature Language="C#" Value="public class AmazonMWSLinkedService : Microsoft.Azure.Management.DataFactory.Models.LinkedService" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit AmazonMWSLinkedService extends Microsoft.Azure.Management.DataFactory.Models.LinkedService" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.DataFactory.Models.AmazonMWSLinkedService" />
  <TypeSignature Language="VB.NET" Value="Public Class AmazonMWSLinkedService&#xA;Inherits LinkedService" />
  <TypeSignature Language="F#" Value="type AmazonMWSLinkedService = class&#xA;    inherit LinkedService" />
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
      <AttributeName>Newtonsoft.Json.JsonObject("AmazonMWS")</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            Amazon-Marketplace-Webdienst verknüpfter Dienst.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public AmazonMWSLinkedService ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.Models.AmazonMWSLinkedService.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            Initialisiert eine neue Instanz der AmazonMWSLinkedService-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public AmazonMWSLinkedService (object endpoint, object marketplaceID, object sellerID, object accessKeyId, System.Collections.Generic.IDictionary&lt;string,object&gt; additionalProperties = null, Microsoft.Azure.Management.DataFactory.Models.IntegrationRuntimeReference connectVia = null, string description = null, Microsoft.Azure.Management.DataFactory.Models.SecretBase mwsAuthToken = null, Microsoft.Azure.Management.DataFactory.Models.SecretBase secretKey = null, object useEncryptedEndpoints = null, object useHostVerification = null, object usePeerVerification = null, object encryptedCredential = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(object endpoint, object marketplaceID, object sellerID, object accessKeyId, class System.Collections.Generic.IDictionary`2&lt;string, object&gt; additionalProperties, class Microsoft.Azure.Management.DataFactory.Models.IntegrationRuntimeReference connectVia, string description, class Microsoft.Azure.Management.DataFactory.Models.SecretBase mwsAuthToken, class Microsoft.Azure.Management.DataFactory.Models.SecretBase secretKey, object useEncryptedEndpoints, object useHostVerification, object usePeerVerification, object encryptedCredential) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.Models.AmazonMWSLinkedService.#ctor(System.Object,System.Object,System.Object,System.Object,System.Collections.Generic.IDictionary{System.String,System.Object},Microsoft.Azure.Management.DataFactory.Models.IntegrationRuntimeReference,System.String,Microsoft.Azure.Management.DataFactory.Models.SecretBase,Microsoft.Azure.Management.DataFactory.Models.SecretBase,System.Object,System.Object,System.Object,System.Object)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (endpoint As Object, marketplaceID As Object, sellerID As Object, accessKeyId As Object, Optional additionalProperties As IDictionary(Of String, Object) = null, Optional connectVia As IntegrationRuntimeReference = null, Optional description As String = null, Optional mwsAuthToken As SecretBase = null, Optional secretKey As SecretBase = null, Optional useEncryptedEndpoints As Object = null, Optional useHostVerification As Object = null, Optional usePeerVerification As Object = null, Optional encryptedCredential As Object = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.DataFactory.Models.AmazonMWSLinkedService : obj * obj * obj * obj * System.Collections.Generic.IDictionary&lt;string, obj&gt; * Microsoft.Azure.Management.DataFactory.Models.IntegrationRuntimeReference * string * Microsoft.Azure.Management.DataFactory.Models.SecretBase * Microsoft.Azure.Management.DataFactory.Models.SecretBase * obj * obj * obj * obj -&gt; Microsoft.Azure.Management.DataFactory.Models.AmazonMWSLinkedService" Usage="new Microsoft.Azure.Management.DataFactory.Models.AmazonMWSLinkedService (endpoint, marketplaceID, sellerID, accessKeyId, additionalProperties, connectVia, description, mwsAuthToken, secretKey, useEncryptedEndpoints, useHostVerification, usePeerVerification, encryptedCredential)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="endpoint" Type="System.Object" />
        <Parameter Name="marketplaceID" Type="System.Object" />
        <Parameter Name="sellerID" Type="System.Object" />
        <Parameter Name="accessKeyId" Type="System.Object" />
        <Parameter Name="additionalProperties" Type="System.Collections.Generic.IDictionary&lt;System.String,System.Object&gt;" />
        <Parameter Name="connectVia" Type="Microsoft.Azure.Management.DataFactory.Models.IntegrationRuntimeReference" />
        <Parameter Name="description" Type="System.String" />
        <Parameter Name="mwsAuthToken" Type="Microsoft.Azure.Management.DataFactory.Models.SecretBase" />
        <Parameter Name="secretKey" Type="Microsoft.Azure.Management.DataFactory.Models.SecretBase" />
        <Parameter Name="useEncryptedEndpoints" Type="System.Object" />
        <Parameter Name="useHostVerification" Type="System.Object" />
        <Parameter Name="usePeerVerification" Type="System.Object" />
        <Parameter Name="encryptedCredential" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="endpoint">Der Endpunkt der Amazon MWS-Servers (d. h. mws.amazonservices.com)</param>
        <param name="marketplaceID">Die Amazon Marketplace-ID, aus der Daten abgerufen werden sollen. Zum Abrufen von Daten aus mehreren Marketplace-IDs trennen Sie diese durch ein Komma (,) ein. (d. h. A2EUQ1WTGCTBG2)</param>
        <param name="sellerID">Die Amazon-Verkäufer-ID.</param>
        <param name="accessKeyId">Die Access-Id verwendet, um auf Daten zugreifen.</param>
        <param name="additionalProperties">Nicht übereinstimmende Eigenschaften aus der Nachricht deserialisiert werden diese Sammlung</param>
        <param name="connectVia">Der Integration Common Language Runtime-Verweis.</param>
        <param name="description">Beschreibung des verknüpften Diensts.</param>
        <param name="mwsAuthToken">Das Amazon MWS-Authentifizierungstoken.</param>
        <param name="secretKey">Der geheime Schlüssel, mit dem auf Daten zugegriffen wird.</param>
        <param name="useEncryptedEndpoints">Gibt an, ob die Endpunkte der Datenquelle mit HTTPS verschlüsselt sind. Der Standardwert lautet „true“.</param>
        <param name="useHostVerification">Gibt an, ob der Hostname im Zertifikat des Servers mit dem Hostnamen des Servers übereinstimmen muss, wenn eine Verbindung über SSL hergestellt wird. Der Standardwert lautet „true“.</param>
        <param name="usePeerVerification">Gibt an, ob die Identität des Servers bei Verbindung über SSL überprüft werden soll. Der Standardwert lautet „true“.</param>
        <param name="encryptedCredential">Die verschlüsselten Anmeldeinformationen für die Authentifizierung verwendet. Anmeldeinformationen werden verschlüsselt, mit dem Integration Runtime Anmeldeinformations-Manager. Typ: Zeichenfolge (oder Ausdruck mit ResultType-Zeichenfolge).</param>
        <summary>
            Initialisiert eine neue Instanz der AmazonMWSLinkedService-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AccessKeyId">
      <MemberSignature Language="C#" Value="public object AccessKeyId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance object AccessKeyId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.AmazonMWSLinkedService.AccessKeyId" />
      <MemberSignature Language="VB.NET" Value="Public Property AccessKeyId As Object" />
      <MemberSignature Language="F#" Value="member this.AccessKeyId : obj with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.AmazonMWSLinkedService.AccessKeyId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="typeProperties.accessKeyId")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Object</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt die Access-Id, die auf Daten zugegriffen hat.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EncryptedCredential">
      <MemberSignature Language="C#" Value="public object EncryptedCredential { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance object EncryptedCredential" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.AmazonMWSLinkedService.EncryptedCredential" />
      <MemberSignature Language="VB.NET" Value="Public Property EncryptedCredential As Object" />
      <MemberSignature Language="F#" Value="member this.EncryptedCredential : obj with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.AmazonMWSLinkedService.EncryptedCredential" />
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
    <Member MemberName="Endpoint">
      <MemberSignature Language="C#" Value="public object Endpoint { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance object Endpoint" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.AmazonMWSLinkedService.Endpoint" />
      <MemberSignature Language="VB.NET" Value="Public Property Endpoint As Object" />
      <MemberSignature Language="F#" Value="member this.Endpoint : obj with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.AmazonMWSLinkedService.Endpoint" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="typeProperties.endpoint")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Object</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt den Endpunkt des Servers Amazon MWS, (d. h. mws.amazonservices.com)
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MarketplaceID">
      <MemberSignature Language="C#" Value="public object MarketplaceID { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance object MarketplaceID" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.AmazonMWSLinkedService.MarketplaceID" />
      <MemberSignature Language="VB.NET" Value="Public Property MarketplaceID As Object" />
      <MemberSignature Language="F#" Value="member this.MarketplaceID : obj with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.AmazonMWSLinkedService.MarketplaceID" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="typeProperties.marketplaceID")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Object</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt die Amazon-Marketplace-ID, die Daten abgerufen werden sollen. Zum Abrufen von Daten aus mehreren Marketplace-IDs trennen Sie diese durch ein Komma (,) ein. (d. h. A2EUQ1WTGCTBG2)
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MwsAuthToken">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.DataFactory.Models.SecretBase MwsAuthToken { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.DataFactory.Models.SecretBase MwsAuthToken" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.AmazonMWSLinkedService.MwsAuthToken" />
      <MemberSignature Language="VB.NET" Value="Public Property MwsAuthToken As SecretBase" />
      <MemberSignature Language="F#" Value="member this.MwsAuthToken : Microsoft.Azure.Management.DataFactory.Models.SecretBase with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.AmazonMWSLinkedService.MwsAuthToken" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="typeProperties.mwsAuthToken")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.DataFactory.Models.SecretBase</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Abrufen oder Festlegen der Amazon MWS Authentifizierungstoken.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SecretKey">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.DataFactory.Models.SecretBase SecretKey { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.DataFactory.Models.SecretBase SecretKey" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.AmazonMWSLinkedService.SecretKey" />
      <MemberSignature Language="VB.NET" Value="Public Property SecretKey As SecretBase" />
      <MemberSignature Language="F#" Value="member this.SecretKey : Microsoft.Azure.Management.DataFactory.Models.SecretBase with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.AmazonMWSLinkedService.SecretKey" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="typeProperties.secretKey")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.DataFactory.Models.SecretBase</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab, oder legt ihn fest den geheimen Schlüssel, die auf Daten zugegriffen hat.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SellerID">
      <MemberSignature Language="C#" Value="public object SellerID { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance object SellerID" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.AmazonMWSLinkedService.SellerID" />
      <MemberSignature Language="VB.NET" Value="Public Property SellerID As Object" />
      <MemberSignature Language="F#" Value="member this.SellerID : obj with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.AmazonMWSLinkedService.SellerID" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="typeProperties.sellerID")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Object</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt die Amazon Verkäufer-ID.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UseEncryptedEndpoints">
      <MemberSignature Language="C#" Value="public object UseEncryptedEndpoints { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance object UseEncryptedEndpoints" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.AmazonMWSLinkedService.UseEncryptedEndpoints" />
      <MemberSignature Language="VB.NET" Value="Public Property UseEncryptedEndpoints As Object" />
      <MemberSignature Language="F#" Value="member this.UseEncryptedEndpoints : obj with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.AmazonMWSLinkedService.UseEncryptedEndpoints" />
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
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.AmazonMWSLinkedService.UseHostVerification" />
      <MemberSignature Language="VB.NET" Value="Public Property UseHostVerification As Object" />
      <MemberSignature Language="F#" Value="member this.UseHostVerification : obj with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.AmazonMWSLinkedService.UseHostVerification" />
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
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.AmazonMWSLinkedService.UsePeerVerification" />
      <MemberSignature Language="VB.NET" Value="Public Property UsePeerVerification As Object" />
      <MemberSignature Language="F#" Value="member this.UsePeerVerification : obj with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.AmazonMWSLinkedService.UsePeerVerification" />
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
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.Models.AmazonMWSLinkedService.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Sub Validate ()" />
      <MemberSignature Language="F#" Value="override this.Validate : unit -&gt; unit" Usage="amazonMWSLinkedService.Validate " />
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