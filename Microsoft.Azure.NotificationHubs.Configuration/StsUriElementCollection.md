<Type Name="StsUriElementCollection" FullName="Microsoft.Azure.NotificationHubs.Configuration.StsUriElementCollection">
  <TypeSignature Language="C#" Value="public sealed class StsUriElementCollection : System.Configuration.ConfigurationElementCollection" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit StsUriElementCollection extends System.Configuration.ConfigurationElementCollection" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.NotificationHubs.Configuration.StsUriElementCollection" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class StsUriElementCollection&#xA;Inherits ConfigurationElementCollection" />
  <TypeSignature Language="F#" Value="type StsUriElementCollection = class&#xA;    inherit ConfigurationElementCollection" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
    <AssemblyVersion>2.16.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Configuration.ConfigurationElementCollection</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>System.Configuration.ConfigurationCollection(typeof(Microsoft.Azure.NotificationHubs.Configuration.StsUriElement), AddItemName="stsUri", CollectionType=System.Configuration.ConfigurationElementCollectionType.BasicMap)</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>Stellt eine Auflistung der URI-Element für den Sicherheitstokendienst dar.</summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public StsUriElementCollection ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.Configuration.StsUriElementCollection.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>Initialisiert eine neue Instanz der <see cref="T:Microsoft.Azure.NotificationHubs.Configuration.StsUriElementCollection" />-Klasse.</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Addresses">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IEnumerable&lt;Uri&gt; Addresses { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IEnumerable`1&lt;class System.Uri&gt; Addresses" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.NotificationHubs.Configuration.StsUriElementCollection.Addresses" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Addresses As IEnumerable(Of Uri)" />
      <MemberSignature Language="F#" Value="member this.Addresses : seq&lt;Uri&gt;" Usage="Microsoft.Azure.NotificationHubs.Configuration.StsUriElementCollection.Addresses" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IEnumerable&lt;System.Uri&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>Ruft die Adressen des Elements in der Auflistung ab.</summary>
        <value>Die Adressen des Elements in der Auflistung.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateNewElement">
      <MemberSignature Language="C#" Value="protected override System.Configuration.ConfigurationElement CreateNewElement ();" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig virtual instance class System.Configuration.ConfigurationElement CreateNewElement() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.Configuration.StsUriElementCollection.CreateNewElement" />
      <MemberSignature Language="VB.NET" Value="Protected Overrides Function CreateNewElement () As ConfigurationElement" />
      <MemberSignature Language="F#" Value="override this.CreateNewElement : unit -&gt; System.Configuration.ConfigurationElement" Usage="stsUriElementCollection.CreateNewElement " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Configuration.ConfigurationElement</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            Erstellt beim Überschreiben in einer abgeleiteten Klasse einen neuen <see cref="T:System.Configuration.ConfigurationElement" />.
            </summary>
        <returns>
            Ein neuer <see cref="T:System.Configuration.ConfigurationElement" />.
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ElementName">
      <MemberSignature Language="C#" Value="protected override string ElementName { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ElementName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.NotificationHubs.Configuration.StsUriElementCollection.ElementName" />
      <MemberSignature Language="VB.NET" Value="Protected Overrides ReadOnly Property ElementName As String" />
      <MemberSignature Language="F#" Value="member this.ElementName : string" Usage="Microsoft.Azure.NotificationHubs.Configuration.StsUriElementCollection.ElementName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft den Namen zum Identifizieren dieser Auflistung von Elementen in der Konfigurationsdatei beim Überschreiben in einer abgeleiteten Klasse.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetElementKey">
      <MemberSignature Language="C#" Value="protected override object GetElementKey (System.Configuration.ConfigurationElement element);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig virtual instance object GetElementKey(class System.Configuration.ConfigurationElement element) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.Configuration.StsUriElementCollection.GetElementKey(System.Configuration.ConfigurationElement)" />
      <MemberSignature Language="VB.NET" Value="Protected Overrides Function GetElementKey (element As ConfigurationElement) As Object" />
      <MemberSignature Language="F#" Value="override this.GetElementKey : System.Configuration.ConfigurationElement -&gt; obj" Usage="stsUriElementCollection.GetElementKey element" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Object</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="element" Type="System.Configuration.ConfigurationElement" />
      </Parameters>
      <Docs>
        <param name="element">Das <see cref="T:System.Configuration.ConfigurationElement" />, für das der Schlüssel zurückzugeben ist.</param>
        <summary>
            Ruft den Elementschlüssel für ein angegebenes Konfigurationselement beim Überschreiben in einer abgeleiteten Klasse ab.
            </summary>
        <returns>
            Ein <see cref="T:System.Object" /> , fungiert als Schlüssel für den angegebenen <see cref="T:System.Configuration.ConfigurationElement" />.
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IsElementName">
      <MemberSignature Language="C#" Value="protected override bool IsElementName (string elementName);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig virtual instance bool IsElementName(string elementName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.Configuration.StsUriElementCollection.IsElementName(System.String)" />
      <MemberSignature Language="VB.NET" Value="Protected Overrides Function IsElementName (elementName As String) As Boolean" />
      <MemberSignature Language="F#" Value="override this.IsElementName : string -&gt; bool" Usage="stsUriElementCollection.IsElementName elementName" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="elementName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="elementName">Der Name des zu überprüfenden Elements.</param>
        <summary>
            Gibt an, ob das angegebene <see cref="T:System.Configuration.ConfigurationElement" /> vorhanden ist, der <see cref="T:System.Configuration.ConfigurationElementCollection" />.
            </summary>
        <returns>
            "true", wenn das Element in der Auflistung vorhanden ist; andernfalls "false". Der Standardwert ist false.
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>