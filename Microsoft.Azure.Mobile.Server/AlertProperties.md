<Type Name="AlertProperties" FullName="Microsoft.Azure.Mobile.Server.AlertProperties">
  <TypeSignature Language="C#" Value="public class AlertProperties : System.Collections.Generic.Dictionary&lt;string,object&gt;" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi serializable beforefieldinit AlertProperties extends System.Collections.Generic.Dictionary`2&lt;string, object&gt;" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Mobile.Server.AlertProperties" />
  <TypeSignature Language="VB.NET" Value="Public Class AlertProperties&#xA;Inherits Dictionary(Of String, Object)" />
  <TypeSignature Language="F#" Value="type AlertProperties = class&#xA;    inherit Dictionary&lt;string, obj&gt;" />
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
            Die Eigenschaft "Warnung" enthält Eigenschaften, die spezifisch für die Warnung in einer Benachrichtigung mit dem Apple Push Notification Service (APNS) abzielen. Richtet sich aus der <see cref="T:Microsoft.Azure.Mobile.Server.ApplePushMessage" /> Klasse.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public AlertProperties ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Mobile.Server.AlertProperties.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Server.Notifications</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            Initialisiert eine neue Instanz der <see cref="T:Microsoft.Azure.Mobile.Server.AlertProperties" />-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="protected AlertProperties (System.Runtime.Serialization.SerializationInfo info, System.Runtime.Serialization.StreamingContext context);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig specialname rtspecialname instance void .ctor(class System.Runtime.Serialization.SerializationInfo info, valuetype System.Runtime.Serialization.StreamingContext context) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Mobile.Server.AlertProperties.#ctor(System.Runtime.Serialization.SerializationInfo,System.Runtime.Serialization.StreamingContext)" />
      <MemberSignature Language="VB.NET" Value="Protected Sub New (info As SerializationInfo, context As StreamingContext)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Mobile.Server.AlertProperties : System.Runtime.Serialization.SerializationInfo * System.Runtime.Serialization.StreamingContext -&gt; Microsoft.Azure.Mobile.Server.AlertProperties" Usage="new Microsoft.Azure.Mobile.Server.AlertProperties (info, context)" />
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
        <param name="info">Ein <see cref="T:System.Runtime.Serialization.SerializationInfo" /> mit Informationen über die <see cref="T:Microsoft.Azure.Mobile.Server.AlertProperties" /> initialisiert werden.</param>
        <param name="context">Ein <see cref="T:System.Runtime.Serialization.StreamingContext" /> , der die Quellinformationen Ziel und Kontext eines serialisierten Streams angibt.</param>
        <summary>
            Initialisiert eine neue Instanz der <see cref="T:Microsoft.Azure.Mobile.Server.AlertProperties" />-Klasse mit den angegebenen Serialisierungsinformationen und dem angegebenen Streamingkontext.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ActionLocKey">
      <MemberSignature Language="C#" Value="public string ActionLocKey { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ActionLocKey" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Mobile.Server.AlertProperties.ActionLocKey" />
      <MemberSignature Language="VB.NET" Value="Public Property ActionLocKey As String" />
      <MemberSignature Language="F#" Value="member this.ActionLocKey : string with get, set" Usage="Microsoft.Azure.Mobile.Server.AlertProperties.ActionLocKey" />
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
            Wenn eine Zeichenfolge angegeben wird, wird das System eine Warnung mit zwei Schaltflächen angezeigt. Die Zeichenfolge wird als Schlüssel verwendet, eine lokalisierte Zeichenfolge in die aktuelle Lokalisierung, verwenden Sie für die rechte Maustaste Titel anstelle von "View" abgerufen.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Body">
      <MemberSignature Language="C#" Value="public string Body { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Body" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Mobile.Server.AlertProperties.Body" />
      <MemberSignature Language="VB.NET" Value="Public Property Body As String" />
      <MemberSignature Language="F#" Value="member this.Body : string with get, set" Usage="Microsoft.Azure.Mobile.Server.AlertProperties.Body" />
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
            Der Text der Warnmeldung an.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="LaunchImage">
      <MemberSignature Language="C#" Value="public string LaunchImage { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string LaunchImage" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Mobile.Server.AlertProperties.LaunchImage" />
      <MemberSignature Language="VB.NET" Value="Public Property LaunchImage As String" />
      <MemberSignature Language="F#" Value="member this.LaunchImage : string with get, set" Usage="Microsoft.Azure.Mobile.Server.AlertProperties.LaunchImage" />
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
            Der Dateiname einer Bilddatei im Anwendungspaket; Sie können Erweiterung, oder lassen sie. Das Bild wird als Start-Image verwendet, wenn Benutzer Tippen Sie auf die Aktionsschaltfläche oder verschieben Sie den Aktionsschieberegler. Wenn diese Eigenschaft nicht angegeben wird, das System entweder verwendet den vorherigen Momentaufnahme, verwendet das Bild, das durch den UILaunchImageFile-Schlüssel in der Anwendungsverzeichnis identifiziert <c>"Info.plist"</c> Datei- oder fragt <c>Default.png</c>.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="LocKey">
      <MemberSignature Language="C#" Value="public string LocKey { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string LocKey" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Mobile.Server.AlertProperties.LocKey" />
      <MemberSignature Language="VB.NET" Value="Public Property LocKey As String" />
      <MemberSignature Language="F#" Value="member this.LocKey : string with get, set" Usage="Microsoft.Azure.Mobile.Server.AlertProperties.LocKey" />
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
            Ein Schlüssel auf eine Warnmeldung Zeichenfolge in eine <c>Localizable.strings</c> -Datei für die aktuelle Lokalisierung (die von der benutzerspracheinstellung festgelegt wird). Der Schlüsselzeichenfolge formatiert werden kann, mit <c> %@ </c> und <c> %n$@ </c> Spezifizierer auszuführenden Variablen in <c>Loc Args</c>. 
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="LogArgs">
      <MemberSignature Language="C#" Value="public System.Collections.ObjectModel.Collection&lt;string&gt; LogArgs { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.ObjectModel.Collection`1&lt;string&gt; LogArgs" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Mobile.Server.AlertProperties.LogArgs" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property LogArgs As Collection(Of String)" />
      <MemberSignature Language="F#" Value="member this.LogArgs : System.Collections.ObjectModel.Collection&lt;string&gt;" Usage="Microsoft.Azure.Mobile.Server.AlertProperties.LogArgs" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Server.Notifications</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.ObjectModel.Collection&lt;System.String&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Variable Zeichenfolgenwerte anstelle Formatbezeichner im angezeigt <c>Loc schlüsselbezogene</c>.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>