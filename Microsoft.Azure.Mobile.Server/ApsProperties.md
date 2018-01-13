<Type Name="ApsProperties" FullName="Microsoft.Azure.Mobile.Server.ApsProperties">
  <TypeSignature Language="C#" Value="public class ApsProperties : System.Collections.Generic.Dictionary&lt;string,object&gt;" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi serializable beforefieldinit ApsProperties extends System.Collections.Generic.Dictionary`2&lt;string, object&gt;" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Mobile.Server.ApsProperties" />
  <TypeSignature Language="VB.NET" Value="Public Class ApsProperties&#xA;Inherits Dictionary(Of String, Object)" />
  <TypeSignature Language="F#" Value="type ApsProperties = class&#xA;    inherit Dictionary&lt;string, obj&gt;" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Mobile.Server.Notifications</AssemblyName>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Collections.Generic.Dictionary&lt;System.String,System.Object&gt;</BaseTypeName>
    <BaseTypeArguments>
      <BaseTypeArgument TypeParamName="!0">System.String</BaseTypeArgument>
      <BaseTypeArgument TypeParamName="!1">System.Object</BaseTypeArgument>
    </BaseTypeArguments>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>System.Diagnostics.CodeAnalysis.SuppressMessage("Microsoft.Naming", "CA1710:IdentifiersShouldHaveCorrectSuffix", Justification="This is a property bag.")</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            Die Eigenschaft "Aps" enthält die Definition einer Benachrichtigung mit dem Apple Push Notification Service (APNS) abzielen. Richtet sich aus der <see cref="T:Microsoft.Azure.Mobile.Server.ApplePushMessage" /> Klasse.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ApsProperties ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Mobile.Server.ApsProperties.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Server.Notifications</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            Initialisiert eine neue Instanz der <see cref="T:Microsoft.Azure.Mobile.Server.ApsProperties" />-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="protected ApsProperties (System.Runtime.Serialization.SerializationInfo info, System.Runtime.Serialization.StreamingContext context);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig specialname rtspecialname instance void .ctor(class System.Runtime.Serialization.SerializationInfo info, valuetype System.Runtime.Serialization.StreamingContext context) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Mobile.Server.ApsProperties.#ctor(System.Runtime.Serialization.SerializationInfo,System.Runtime.Serialization.StreamingContext)" />
      <MemberSignature Language="VB.NET" Value="Protected Sub New (info As SerializationInfo, context As StreamingContext)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Mobile.Server.ApsProperties : System.Runtime.Serialization.SerializationInfo * System.Runtime.Serialization.StreamingContext -&gt; Microsoft.Azure.Mobile.Server.ApsProperties" Usage="new Microsoft.Azure.Mobile.Server.ApsProperties (info, context)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Server.Notifications</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="info" Type="System.Runtime.Serialization.SerializationInfo" />
        <Parameter Name="context" Type="System.Runtime.Serialization.StreamingContext" />
      </Parameters>
      <Docs>
        <param name="info">Ein <see cref="T:System.Runtime.Serialization.SerializationInfo" /> mit Informationen über die <see cref="T:Microsoft.Azure.Mobile.Server.ApsProperties" /> initialisiert werden.</param>
        <param name="context">Ein <see cref="T:System.Runtime.Serialization.StreamingContext" /> , der die Quellinformationen Ziel und Kontext eines serialisierten Streams angibt.</param>
        <summary>
            Initialisiert eine neue Instanz der <see cref="T:Microsoft.Azure.Mobile.Server.ApsProperties" />-Klasse mit den angegebenen Serialisierungsinformationen und dem angegebenen Streamingkontext.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Alert">
      <MemberSignature Language="C#" Value="public string Alert { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Alert" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Mobile.Server.ApsProperties.Alert" />
      <MemberSignature Language="VB.NET" Value="Public Property Alert As String" />
      <MemberSignature Language="F#" Value="member this.Alert : string with get, set" Usage="Microsoft.Azure.Mobile.Server.ApsProperties.Alert" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Server.Notifications</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Die Warnmeldung als einzelne Zeichenfolge. Verwenden Sie für eine komplexere Warnmeldung Optionen <see cref="M:AlertProperties" />.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AlertProperties">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Mobile.Server.AlertProperties AlertProperties { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Mobile.Server.AlertProperties AlertProperties" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Mobile.Server.ApsProperties.AlertProperties" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property AlertProperties As AlertProperties" />
      <MemberSignature Language="F#" Value="member this.AlertProperties : Microsoft.Azure.Mobile.Server.AlertProperties" Usage="Microsoft.Azure.Mobile.Server.ApsProperties.AlertProperties" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Server.Notifications</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Mobile.Server.AlertProperties</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Warnmeldung als Wörterbuch mit zusätzlichen Eigenschaften, die die Warnung z. B. Lokalisierungsinformationen, beschreibt das Bild angezeigt werden, usw. Wenn die Warnung ist, dann stellen Sie einfach eine Zeichenfolge verwenden <see cref="M:Alert" />.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Badge">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; Badge { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; Badge" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Mobile.Server.ApsProperties.Badge" />
      <MemberSignature Language="VB.NET" Value="Public Property Badge As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.Badge : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Mobile.Server.ApsProperties.Badge" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Server.Notifications</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Die Anzahl als das Signal für das Anwendungssymbol angezeigt. Wenn diese Eigenschaft nicht vorhanden ist, wird das Signal nicht geändert. Um das Signal zu entfernen, wird den Wert dieser Eigenschaft auf 0 festgelegt.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ContentAvailable">
      <MemberSignature Language="C#" Value="public bool ContentAvailable { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool ContentAvailable" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Mobile.Server.ApsProperties.ContentAvailable" />
      <MemberSignature Language="VB.NET" Value="Public Property ContentAvailable As Boolean" />
      <MemberSignature Language="F#" Value="member this.ContentAvailable : bool with get, set" Usage="Microsoft.Azure.Mobile.Server.ApsProperties.ContentAvailable" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Server.Notifications</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Geben Sie diesen Schlüssel, mit dem Wert 1 fest, um anzugeben, dass der neue Inhalt verfügbar ist. Dies dient zur Unterstützung von Newsstand apps und Hintergrund Inhalt heruntergeladen wird.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Sound">
      <MemberSignature Language="C#" Value="public string Sound { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Sound" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Mobile.Server.ApsProperties.Sound" />
      <MemberSignature Language="VB.NET" Value="Public Property Sound As String" />
      <MemberSignature Language="F#" Value="member this.Sound : string with get, set" Usage="Microsoft.Azure.Mobile.Server.ApsProperties.Sound" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Server.Notifications</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Der Name einer Audiodatei im Anwendungspaket. Der Sound in dieser Datei wird als Warnung wiedergegeben. Wenn die Audiodatei nicht vorhanden, oder Standardwert als Wert angegeben ist, wird das Standardwarnsignal wiedergegeben. Die Audiodatei muss in einem der audiodatenformate sein, die mit Systemsounds kompatibel sind. 
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>