<Type Name="WebActivity" FullName="Microsoft.Azure.Management.DataFactory.Models.WebActivity">
  <TypeSignature Language="C#" Value="public class WebActivity : Microsoft.Azure.Management.DataFactory.Models.ExecutionActivity" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit WebActivity extends Microsoft.Azure.Management.DataFactory.Models.ExecutionActivity" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.DataFactory.Models.WebActivity" />
  <TypeSignature Language="VB.NET" Value="Public Class WebActivity&#xA;Inherits ExecutionActivity" />
  <TypeSignature Language="F#" Value="type WebActivity = class&#xA;    inherit ExecutionActivity" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
    <AssemblyVersion>0.2.0.0</AssemblyVersion>
    <AssemblyVersion>0.3.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Management.DataFactory.Models.ExecutionActivity</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>Microsoft.Rest.Serialization.JsonTransformation</AttributeName>
    </Attribute>
    <Attribute>
      <AttributeName>Newtonsoft.Json.JsonObject("WebActivity")</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            Webaktivität.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public WebActivity ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.Models.WebActivity.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            Initialisiert eine neue Instanz der WebActivity-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public WebActivity (string name, string method, object url, System.Collections.Generic.IDictionary&lt;string,object&gt; additionalProperties = null, string description = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Management.DataFactory.Models.ActivityDependency&gt; dependsOn = null, Microsoft.Azure.Management.DataFactory.Models.LinkedServiceReference linkedServiceName = null, Microsoft.Azure.Management.DataFactory.Models.ActivityPolicy policy = null, object headers = null, object body = null, Microsoft.Azure.Management.DataFactory.Models.WebActivityAuthentication authentication = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Management.DataFactory.Models.DatasetReference&gt; datasets = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Management.DataFactory.Models.LinkedServiceReference&gt; linkedServices = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string name, string method, object url, class System.Collections.Generic.IDictionary`2&lt;string, object&gt; additionalProperties, string description, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.DataFactory.Models.ActivityDependency&gt; dependsOn, class Microsoft.Azure.Management.DataFactory.Models.LinkedServiceReference linkedServiceName, class Microsoft.Azure.Management.DataFactory.Models.ActivityPolicy policy, object headers, object body, class Microsoft.Azure.Management.DataFactory.Models.WebActivityAuthentication authentication, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.DataFactory.Models.DatasetReference&gt; datasets, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.DataFactory.Models.LinkedServiceReference&gt; linkedServices) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.Models.WebActivity.#ctor(System.String,System.String,System.Object,System.Collections.Generic.IDictionary{System.String,System.Object},System.String,System.Collections.Generic.IList{Microsoft.Azure.Management.DataFactory.Models.ActivityDependency},Microsoft.Azure.Management.DataFactory.Models.LinkedServiceReference,Microsoft.Azure.Management.DataFactory.Models.ActivityPolicy,System.Object,System.Object,Microsoft.Azure.Management.DataFactory.Models.WebActivityAuthentication,System.Collections.Generic.IList{Microsoft.Azure.Management.DataFactory.Models.DatasetReference},System.Collections.Generic.IList{Microsoft.Azure.Management.DataFactory.Models.LinkedServiceReference})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (name As String, method As String, url As Object, Optional additionalProperties As IDictionary(Of String, Object) = null, Optional description As String = null, Optional dependsOn As IList(Of ActivityDependency) = null, Optional linkedServiceName As LinkedServiceReference = null, Optional policy As ActivityPolicy = null, Optional headers As Object = null, Optional body As Object = null, Optional authentication As WebActivityAuthentication = null, Optional datasets As IList(Of DatasetReference) = null, Optional linkedServices As IList(Of LinkedServiceReference) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.DataFactory.Models.WebActivity : string * string * obj * System.Collections.Generic.IDictionary&lt;string, obj&gt; * string * System.Collections.Generic.IList&lt;Microsoft.Azure.Management.DataFactory.Models.ActivityDependency&gt; * Microsoft.Azure.Management.DataFactory.Models.LinkedServiceReference * Microsoft.Azure.Management.DataFactory.Models.ActivityPolicy * obj * obj * Microsoft.Azure.Management.DataFactory.Models.WebActivityAuthentication * System.Collections.Generic.IList&lt;Microsoft.Azure.Management.DataFactory.Models.DatasetReference&gt; * System.Collections.Generic.IList&lt;Microsoft.Azure.Management.DataFactory.Models.LinkedServiceReference&gt; -&gt; Microsoft.Azure.Management.DataFactory.Models.WebActivity" Usage="new Microsoft.Azure.Management.DataFactory.Models.WebActivity (name, method, url, additionalProperties, description, dependsOn, linkedServiceName, policy, headers, body, authentication, datasets, linkedServices)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="method" Type="System.String" />
        <Parameter Name="url" Type="System.Object" />
        <Parameter Name="additionalProperties" Type="System.Collections.Generic.IDictionary&lt;System.String,System.Object&gt;" />
        <Parameter Name="description" Type="System.String" />
        <Parameter Name="dependsOn" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.DataFactory.Models.ActivityDependency&gt;" />
        <Parameter Name="linkedServiceName" Type="Microsoft.Azure.Management.DataFactory.Models.LinkedServiceReference" />
        <Parameter Name="policy" Type="Microsoft.Azure.Management.DataFactory.Models.ActivityPolicy" />
        <Parameter Name="headers" Type="System.Object" />
        <Parameter Name="body" Type="System.Object" />
        <Parameter Name="authentication" Type="Microsoft.Azure.Management.DataFactory.Models.WebActivityAuthentication" />
        <Parameter Name="datasets" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.DataFactory.Models.DatasetReference&gt;" />
        <Parameter Name="linkedServices" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.DataFactory.Models.LinkedServiceReference&gt;" />
      </Parameters>
      <Docs>
        <param name="name">Der Name der Aktivität.</param>
        <param name="method">REST-API-Methode für den Zielendpunkt. Folgende Werte sind möglich: "GET", "POST", "PUT"</param>
        <param name="url">Zielendpunkt für Web-Aktivität und den Pfad. Typ: Zeichenfolge (oder Ausdruck mit ResultType-Zeichenfolge).</param>
        <param name="additionalProperties">Nicht übereinstimmende Eigenschaften aus der Nachricht deserialisiert werden diese Sammlung</param>
        <param name="description">Beschreibung der Aktivität.</param>
        <param name="dependsOn">Aktivität hängt vom Zustand ab.</param>
        <param name="linkedServiceName">Verknüpften Dienst verweisen.</param>
        <param name="policy">"Aktivitätsrichtlinie".</param>
        <param name="headers">Stellt die Header, die auf die Anforderung gesendet werden. Beispielsweise, um die Sprache und den Typ für eine Anforderung festgelegt: "Header": {"Accept-Language": "En-us", "Content-Type": "Application/Json"}. Typ: Zeichenfolge (oder Ausdruck mit ResultType-Zeichenfolge).</param>
        <param name="body">Stellt die Nutzlast, die an den Endpunkt gesendet werden. Erforderlich für POST/PUT-Methode, für die GET-Methode Typ nicht zulässig: Zeichenfolge (oder einen Ausdruck mit ResultType-Zeichenfolge).</param>
        <param name="authentication">Die zum Aufrufen des Endpunkts verwendete Authentifizierungsmethode.</param>
        <param name="datasets">Liste der Datasets, die an den Webendpunkt übergeben werden.</param>
        <param name="linkedServices">Liste der verknüpften Dienste, die an den Webendpunkt übergeben werden.</param>
        <summary>
            Initialisiert eine neue Instanz der WebActivity-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Authentication">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.DataFactory.Models.WebActivityAuthentication Authentication { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.DataFactory.Models.WebActivityAuthentication Authentication" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.WebActivity.Authentication" />
      <MemberSignature Language="VB.NET" Value="Public Property Authentication As WebActivityAuthentication" />
      <MemberSignature Language="F#" Value="member this.Authentication : Microsoft.Azure.Management.DataFactory.Models.WebActivityAuthentication with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.WebActivity.Authentication" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="typeProperties.authentication")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.DataFactory.Models.WebActivityAuthentication</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab, oder legt ihn fest Authentifizierungsmethode, die zum Aufrufen des Endpunkts verwendet.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Body">
      <MemberSignature Language="C#" Value="public object Body { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance object Body" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.WebActivity.Body" />
      <MemberSignature Language="VB.NET" Value="Public Property Body As Object" />
      <MemberSignature Language="F#" Value="member this.Body : obj with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.WebActivity.Body" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="typeProperties.body")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Object</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt stellt die Nutzlast, die an den Endpunkt gesendet werden. Erforderlich für POST/PUT-Methode, für die GET-Methode Typ nicht zulässig: Zeichenfolge (oder einen Ausdruck mit ResultType-Zeichenfolge).
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Datasets">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.DataFactory.Models.DatasetReference&gt; Datasets { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.DataFactory.Models.DatasetReference&gt; Datasets" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.WebActivity.Datasets" />
      <MemberSignature Language="VB.NET" Value="Public Property Datasets As IList(Of DatasetReference)" />
      <MemberSignature Language="F#" Value="member this.Datasets : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.DataFactory.Models.DatasetReference&gt; with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.WebActivity.Datasets" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="typeProperties.datasets")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.DataFactory.Models.DatasetReference&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt die Liste der Datasets, die an den Webendpunkt übergeben.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Headers">
      <MemberSignature Language="C#" Value="public object Headers { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance object Headers" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.WebActivity.Headers" />
      <MemberSignature Language="VB.NET" Value="Public Property Headers As Object" />
      <MemberSignature Language="F#" Value="member this.Headers : obj with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.WebActivity.Headers" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="typeProperties.headers")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Object</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt stellt die Header, die auf die Anforderung gesendet werden. Beispielsweise, um die Sprache und den Typ für eine Anforderung festgelegt: "Header": {"Accept-Language": "En-us", "Content-Type": "Application/Json"}. Typ: Zeichenfolge (oder Ausdruck mit ResultType-Zeichenfolge).
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="LinkedServices">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.DataFactory.Models.LinkedServiceReference&gt; LinkedServices { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.DataFactory.Models.LinkedServiceReference&gt; LinkedServices" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.WebActivity.LinkedServices" />
      <MemberSignature Language="VB.NET" Value="Public Property LinkedServices As IList(Of LinkedServiceReference)" />
      <MemberSignature Language="F#" Value="member this.LinkedServices : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.DataFactory.Models.LinkedServiceReference&gt; with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.WebActivity.LinkedServices" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="typeProperties.linkedServices")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.DataFactory.Models.LinkedServiceReference&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt die Liste der verknüpften Dienste, die an den Webendpunkt übergeben.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Method">
      <MemberSignature Language="C#" Value="public string Method { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Method" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.WebActivity.Method" />
      <MemberSignature Language="VB.NET" Value="Public Property Method As String" />
      <MemberSignature Language="F#" Value="member this.Method : string with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.WebActivity.Method" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="typeProperties.method")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab, oder legt ihn fest Rest-API-Methode für den Zielendpunkt. Folgende Werte sind möglich: "GET", "POST", "PUT"
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Url">
      <MemberSignature Language="C#" Value="public object Url { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance object Url" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.WebActivity.Url" />
      <MemberSignature Language="VB.NET" Value="Public Property Url As Object" />
      <MemberSignature Language="F#" Value="member this.Url : obj with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.WebActivity.Url" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="typeProperties.url")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Object</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab, oder legt sie fest, Zielendpunkt für Web-Aktivität und den Pfad. Typ: Zeichenfolge (oder Ausdruck mit ResultType-Zeichenfolge).
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public override void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.Models.WebActivity.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Sub Validate ()" />
      <MemberSignature Language="F#" Value="override this.Validate : unit -&gt; unit" Usage="webActivity.Validate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
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