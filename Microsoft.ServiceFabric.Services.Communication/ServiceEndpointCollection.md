<Type Name="ServiceEndpointCollection" FullName="Microsoft.ServiceFabric.Services.Communication.ServiceEndpointCollection">
  <TypeSignature Language="C#" Value="public sealed class ServiceEndpointCollection" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit ServiceEndpointCollection extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceFabric.Services.Communication.ServiceEndpointCollection" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class ServiceEndpointCollection" />
  <TypeSignature Language="F#" Value="type ServiceEndpointCollection = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.ServiceFabric.Services</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>System.Runtime.Serialization.DataContract</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            Diese Klasse stellt die Endpunkte eines Diensts zuverlässige dar. Jeder Endpunkt hat einen Listenernamen und die Adresse für diesen Listener.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ServiceEndpointCollection ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Services.Communication.ServiceEndpointCollection.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            Instanziiert eine leere ServiceEndpointsCollection an.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ServiceEndpointCollection (string listenerName, string endpointAddress);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string listenerName, string endpointAddress) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Services.Communication.ServiceEndpointCollection.#ctor(System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (listenerName As String, endpointAddress As String)" />
      <MemberSignature Language="F#" Value="new Microsoft.ServiceFabric.Services.Communication.ServiceEndpointCollection : string * string -&gt; Microsoft.ServiceFabric.Services.Communication.ServiceEndpointCollection" Usage="new Microsoft.ServiceFabric.Services.Communication.ServiceEndpointCollection (listenerName, endpointAddress)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="listenerName" Type="System.String" />
        <Parameter Name="endpointAddress" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="listenerName">Verfügbarkeitsgruppenlistener-Namen des Endpunkts</param>
        <param name="endpointAddress">Adresse des Endpunkts</param>
        <summary>
            Instanziiert die ServiceEndpointsCollection mit einem einzelnen Endpunkt, identifiziert durch den Namen des Listeners an.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AddEndpoint">
      <MemberSignature Language="C#" Value="public void AddEndpoint (string listenerName, string endpointAddress);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void AddEndpoint(string listenerName, string endpointAddress) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Services.Communication.ServiceEndpointCollection.AddEndpoint(System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub AddEndpoint (listenerName As String, endpointAddress As String)" />
      <MemberSignature Language="F#" Value="member this.AddEndpoint : string * string -&gt; unit" Usage="serviceEndpointCollection.AddEndpoint (listenerName, endpointAddress)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="listenerName" Type="System.String" />
        <Parameter Name="endpointAddress" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="listenerName">Verfügbarkeitsgruppenlistener-Namen des Endpunkts</param>
        <param name="endpointAddress">Adresse des Endpunkts</param>
        <summary>
            Die EndpointsCollection hinzugefügt einen Endpunkt.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AddEndpoints">
      <MemberSignature Language="C#" Value="public void AddEndpoints (Microsoft.ServiceFabric.Services.Communication.ServiceEndpointCollection newEndpoints);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void AddEndpoints(class Microsoft.ServiceFabric.Services.Communication.ServiceEndpointCollection newEndpoints) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Services.Communication.ServiceEndpointCollection.AddEndpoints(Microsoft.ServiceFabric.Services.Communication.ServiceEndpointCollection)" />
      <MemberSignature Language="VB.NET" Value="Public Sub AddEndpoints (newEndpoints As ServiceEndpointCollection)" />
      <MemberSignature Language="F#" Value="member this.AddEndpoints : Microsoft.ServiceFabric.Services.Communication.ServiceEndpointCollection -&gt; unit" Usage="serviceEndpointCollection.AddEndpoints newEndpoints" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="newEndpoints" Type="Microsoft.ServiceFabric.Services.Communication.ServiceEndpointCollection" />
      </Parameters>
      <Docs>
        <param name="newEndpoints">Eingabe EndpointsCollection</param>
        <summary>
            Die EndpointsCollection hinzugefügt die Endpunkte in der Eingabe EndpointsCollection-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ToReadOnlyDictionary">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IReadOnlyDictionary&lt;string,string&gt; ToReadOnlyDictionary ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Collections.Generic.IReadOnlyDictionary`2&lt;string, string&gt; ToReadOnlyDictionary() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Services.Communication.ServiceEndpointCollection.ToReadOnlyDictionary" />
      <MemberSignature Language="VB.NET" Value="Public Function ToReadOnlyDictionary () As IReadOnlyDictionary(Of String, String)" />
      <MemberSignature Language="F#" Value="member this.ToReadOnlyDictionary : unit -&gt; System.Collections.Generic.IReadOnlyDictionary&lt;string, string&gt;" Usage="serviceEndpointCollection.ToReadOnlyDictionary " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IReadOnlyDictionary&lt;System.String,System.String&gt;</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            Gibt eine ReadOnlyDictionary von der EndpointsCollection zurück.
            </summary>
        <returns>EndpointsCollection als eine ReadOnlyDictionary</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ToString">
      <MemberSignature Language="C#" Value="public override string ToString ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance string ToString() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Services.Communication.ServiceEndpointCollection.ToString" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function ToString () As String" />
      <MemberSignature Language="F#" Value="override this.ToString : unit -&gt; string" Usage="serviceEndpointCollection.ToString " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            Konvertiert die EndpointsCollection in eine JSON-Zeichenfolge des Formulars {"Endpunkte": {"Listener1": "Endpoint1", "Listener2": "Endpoint2"...}}
            </summary>
        <returns>Von der EndpointsCollection in Form einer Zeichenfolge</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TryGetEndpointAddress">
      <MemberSignature Language="C#" Value="public bool TryGetEndpointAddress (string listenerName, out string endpointAddress);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance bool TryGetEndpointAddress(string listenerName, [out] string&amp; endpointAddress) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Services.Communication.ServiceEndpointCollection.TryGetEndpointAddress(System.String,System.String@)" />
      <MemberSignature Language="VB.NET" Value="Public Function TryGetEndpointAddress (listenerName As String, ByRef endpointAddress As String) As Boolean" />
      <MemberSignature Language="F#" Value="member this.TryGetEndpointAddress : string *  -&gt; bool" Usage="serviceEndpointCollection.TryGetEndpointAddress (listenerName, endpointAddress)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="listenerName" Type="System.String" />
        <Parameter Name="endpointAddress" Type="System.String&amp;" RefType="out" />
      </Parameters>
      <Docs>
        <param name="listenerName">Name des Listeners</param>
        <param name="endpointAddress">Die Adresse des Endpunkts, wenn ein Endpunkt mit diesem Listenernamen vorhanden ist.</param>
        <summary>
            Ruft den Endpunkt identifiziert durch den Namen des Listeners an.
            </summary>
        <returns>True, wenn ein Endpunkt mit dem Namen des Listeners "false" vorhanden, andernfalls ist</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TryGetFirstEndpointAddress">
      <MemberSignature Language="C#" Value="public bool TryGetFirstEndpointAddress (out string endpointAddress);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance bool TryGetFirstEndpointAddress([out] string&amp; endpointAddress) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Services.Communication.ServiceEndpointCollection.TryGetFirstEndpointAddress(System.String@)" />
      <MemberSignature Language="VB.NET" Value="Public Function TryGetFirstEndpointAddress (ByRef endpointAddress As String) As Boolean" />
      <MemberSignature Language="F#" Value="member this.TryGetFirstEndpointAddress :  -&gt; bool" Usage="serviceEndpointCollection.TryGetFirstEndpointAddress endpointAddress" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="endpointAddress" Type="System.String&amp;" RefType="out" />
      </Parameters>
      <Docs>
        <param name="endpointAddress">Erste Endpunkt in der EndpointsCollection</param>
        <summary>
            Ruft die erste Adresse des Endpunkts in der EndpointsCollection ab.
            </summary>
        <returns>True, wenn es mindestens einen Endpunkt in der EndpointsCollection "false" andernfalls</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TryParseEndpointsString">
      <MemberSignature Language="C#" Value="public static bool TryParseEndpointsString (string endpointsString, out Microsoft.ServiceFabric.Services.Communication.ServiceEndpointCollection serviceEndpoints);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig bool TryParseEndpointsString(string endpointsString, [out] class Microsoft.ServiceFabric.Services.Communication.ServiceEndpointCollection&amp; serviceEndpoints) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Services.Communication.ServiceEndpointCollection.TryParseEndpointsString(System.String,Microsoft.ServiceFabric.Services.Communication.ServiceEndpointCollection@)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function TryParseEndpointsString (endpointsString As String, ByRef serviceEndpoints As ServiceEndpointCollection) As Boolean" />
      <MemberSignature Language="F#" Value="static member TryParseEndpointsString : string *  -&gt; bool" Usage="Microsoft.ServiceFabric.Services.Communication.ServiceEndpointCollection.TryParseEndpointsString (endpointsString, serviceEndpoints)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="endpointsString" Type="System.String" />
        <Parameter Name="serviceEndpoints" Type="Microsoft.ServiceFabric.Services.Communication.ServiceEndpointCollection&amp;" RefType="out" />
      </Parameters>
      <Docs>
        <param name="endpointsString">der EndpointsCollection in Form einer Zeichenfolge</param>
        <param name="serviceEndpoints">ServiceEndpointCollection-Objekt, wenn die Zeichenfolge kann, um ein gültiges ServiceEndpointCollection-Objekt analysiert werden</param>
        <summary>
            Erstellt eine EndpointsCollection aus eine Zeichenfolgenversion der Endpunkte. Der EndpointsCollection in Form einer Zeichenfolge im Format ist {"Endpunkte": {"Listener1": "Endpoint1", "Listener2": "Endpoint2"...}}
            </summary>
        <returns>"True", wenn die Zeichenfolge andernfalls zu einem gültigen EndpointsCollection, "false" analysiert werden kann</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>