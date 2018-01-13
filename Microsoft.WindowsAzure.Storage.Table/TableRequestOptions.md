<Type Name="TableRequestOptions" FullName="Microsoft.WindowsAzure.Storage.Table.TableRequestOptions">
  <TypeSignature Language="C#" Value="public sealed class TableRequestOptions : Microsoft.WindowsAzure.Storage.IRequestOptions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit TableRequestOptions extends System.Object implements class Microsoft.WindowsAzure.Storage.IRequestOptions" />
  <TypeSignature Language="DocId" Value="T:Microsoft.WindowsAzure.Storage.Table.TableRequestOptions" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class TableRequestOptions&#xA;Implements IRequestOptions" />
  <TypeSignature Language="F#" Value="type TableRequestOptions = class&#xA;    interface IRequestOptions" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
    <AssemblyVersion>8.4.0.0</AssemblyVersion>
    <AssemblyVersion>8.7.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces>
    <Interface>
      <InterfaceName>Microsoft.WindowsAzure.Storage.IRequestOptions</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <summary>
            Stellt eine Reihe von Optionen für Timeout- und wiederholungsrichtlinien, die für eine Anforderung für den Tabellendienst angegeben werden kann.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public TableRequestOptions ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Table.TableRequestOptions.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            Initialisiert eine neue Instanz der <see cref="T:Microsoft.WindowsAzure.Storage.Table.TableRequestOptions" />-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public TableRequestOptions (Microsoft.WindowsAzure.Storage.Table.TableRequestOptions other);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class Microsoft.WindowsAzure.Storage.Table.TableRequestOptions other) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Table.TableRequestOptions.#ctor(Microsoft.WindowsAzure.Storage.Table.TableRequestOptions)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (other As TableRequestOptions)" />
      <MemberSignature Language="F#" Value="new Microsoft.WindowsAzure.Storage.Table.TableRequestOptions : Microsoft.WindowsAzure.Storage.Table.TableRequestOptions -&gt; Microsoft.WindowsAzure.Storage.Table.TableRequestOptions" Usage="new Microsoft.WindowsAzure.Storage.Table.TableRequestOptions other" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="other" Type="Microsoft.WindowsAzure.Storage.Table.TableRequestOptions" />
      </Parameters>
      <Docs>
        <param name="other">Die <see cref="T:Microsoft.WindowsAzure.Storage.Table.TableRequestOptions" /> Objekt verwendet, um eine neue Instanz der Initialisieren der <see cref="T:Microsoft.WindowsAzure.Storage.Table.TableRequestOptions" /> Klasse.</param>
        <summary>
            Initialisiert eine neue Instanz der <see cref="T:Microsoft.WindowsAzure.Storage.Table.TableRequestOptions" />-Klasse mit der angegebenen <see cref="T:Microsoft.WindowsAzure.Storage.Table.TableRequestOptions" />.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EncryptionPolicy">
      <MemberSignature Language="C#" Value="public Microsoft.WindowsAzure.Storage.Table.TableEncryptionPolicy EncryptionPolicy { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.WindowsAzure.Storage.Table.TableEncryptionPolicy EncryptionPolicy" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.Table.TableRequestOptions.EncryptionPolicy" />
      <MemberSignature Language="VB.NET" Value="Public Property EncryptionPolicy As TableEncryptionPolicy" />
      <MemberSignature Language="F#" Value="member this.EncryptionPolicy : Microsoft.WindowsAzure.Storage.Table.TableEncryptionPolicy with get, set" Usage="Microsoft.WindowsAzure.Storage.Table.TableRequestOptions.EncryptionPolicy" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.Table.TableEncryptionPolicy</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt die Verschlüsselungsrichtlinie für die Anforderung.
            </summary>
        <value>Ein Objekt vom Typ <see cref="P:Microsoft.WindowsAzure.Storage.Table.TableRequestOptions.EncryptionPolicy" />.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EncryptionResolver">
      <MemberSignature Language="C#" Value="public Func&lt;string,string,string,bool&gt; EncryptionResolver { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Func`4&lt;string, string, string, bool&gt; EncryptionResolver" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.Table.TableRequestOptions.EncryptionResolver" />
      <MemberSignature Language="VB.NET" Value="Public Property EncryptionResolver As Func(Of String, String, String, Boolean)" />
      <MemberSignature Language="F#" Value="member this.EncryptionResolver : Func&lt;string, string, string, bool&gt; with get, set" Usage="Microsoft.WindowsAzure.Storage.Table.TableRequestOptions.EncryptionResolver" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Func&lt;System.String,System.String,System.String,System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Abrufen oder Festlegen der Delegat, der den Wert, der angibt, und zwar unabhängig davon, ob eine Eigenschaft verschlüsselt werden sollen, erhält die Partitionsschlüssel, Zeilenschlüssel und Eigenschaftsnamen abrufen. 
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="LocationMode">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.WindowsAzure.Storage.RetryPolicies.LocationMode&gt; LocationMode { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.WindowsAzure.Storage.RetryPolicies.LocationMode&gt; LocationMode" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.Table.TableRequestOptions.LocationMode" />
      <MemberSignature Language="VB.NET" Value="Public Property LocationMode As Nullable(Of LocationMode)" />
      <MemberSignature Language="F#" Value="member this.LocationMode : Nullable&lt;Microsoft.WindowsAzure.Storage.RetryPolicies.LocationMode&gt; with get, set" Usage="Microsoft.WindowsAzure.Storage.Table.TableRequestOptions.LocationMode" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.WindowsAzure.Storage.IRequestOptions.LocationMode</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;Microsoft.WindowsAzure.Storage.RetryPolicies.LocationMode&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt den Positionsmodus der Anforderung fest.
            </summary>
        <value>Ein <see cref="T:Microsoft.WindowsAzure.Storage.RetryPolicies.LocationMode" /> -Enumerationswert, der angibt, des Positionsmodus der Anforderung.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MaximumExecutionTime">
      <MemberSignature Language="C#" Value="public Nullable&lt;TimeSpan&gt; MaximumExecutionTime { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.TimeSpan&gt; MaximumExecutionTime" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.Table.TableRequestOptions.MaximumExecutionTime" />
      <MemberSignature Language="VB.NET" Value="Public Property MaximumExecutionTime As Nullable(Of TimeSpan)" />
      <MemberSignature Language="F#" Value="member this.MaximumExecutionTime : Nullable&lt;TimeSpan&gt; with get, set" Usage="Microsoft.WindowsAzure.Storage.Table.TableRequestOptions.MaximumExecutionTime" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.WindowsAzure.Storage.IRequestOptions.MaximumExecutionTime</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.TimeSpan&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt die maximale Ausführungszeit für alle möglichen Wiederholungen für die Anforderung.
            </summary>
        <value>Ein <see cref="T:System.TimeSpan" /> , die die maximale Ausführungszeit für Wiederholungen für die Anforderung darstellt.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PayloadFormat">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.WindowsAzure.Storage.Table.TablePayloadFormat&gt; PayloadFormat { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.WindowsAzure.Storage.Table.TablePayloadFormat&gt; PayloadFormat" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.Table.TableRequestOptions.PayloadFormat" />
      <MemberSignature Language="VB.NET" Value="Public Property PayloadFormat As Nullable(Of TablePayloadFormat)" />
      <MemberSignature Language="F#" Value="member this.PayloadFormat : Nullable&lt;Microsoft.WindowsAzure.Storage.Table.TablePayloadFormat&gt; with get, set" Usage="Microsoft.WindowsAzure.Storage.Table.TableRequestOptions.PayloadFormat" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;Microsoft.WindowsAzure.Storage.Table.TablePayloadFormat&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt die <see cref="T:Microsoft.WindowsAzure.Storage.Table.TablePayloadFormat" /> , für die Anforderung verwendet wird.
            </summary>
        <value>Ein <see cref="T:Microsoft.WindowsAzure.Storage.Table.TablePayloadFormat" />-Enumerationswert.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ProjectSystemProperties">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; ProjectSystemProperties { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; ProjectSystemProperties" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.Table.TableRequestOptions.ProjectSystemProperties" />
      <MemberSignature Language="VB.NET" Value="Public Property ProjectSystemProperties As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.ProjectSystemProperties : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.WindowsAzure.Storage.Table.TableRequestOptions.ProjectSystemProperties" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt die Option zum Einbeziehen von Systemeigenschaften wie z. B. Partitionsschlüssel und Zeilenschlüssel in Abfragen.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PropertyResolver">
      <MemberSignature Language="C#" Value="public Func&lt;string,string,string,string,Microsoft.WindowsAzure.Storage.Table.EdmType&gt; PropertyResolver { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Func`5&lt;string, string, string, string, valuetype Microsoft.WindowsAzure.Storage.Table.EdmType&gt; PropertyResolver" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.Table.TableRequestOptions.PropertyResolver" />
      <MemberSignature Language="VB.NET" Value="Public Property PropertyResolver As Func(Of String, String, String, String, EdmType)" />
      <MemberSignature Language="F#" Value="member this.PropertyResolver : Func&lt;string, string, string, string, Microsoft.WindowsAzure.Storage.Table.EdmType&gt; with get, set" Usage="Microsoft.WindowsAzure.Storage.Table.TableRequestOptions.PropertyResolver" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Func&lt;System.String,System.String,System.String,System.String,Microsoft.WindowsAzure.Storage.Table.EdmType&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt den Delegaten ab, das Abrufen der <see cref="T:Microsoft.WindowsAzure.Storage.Table.EdmType" /> für eine Entitätseigenschaft, die den Partitionsschlüssel, Zeilenschlüssel und den Namen der Eigenschaft zugewiesen. 
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RequireEncryption">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; RequireEncryption { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; RequireEncryption" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.Table.TableRequestOptions.RequireEncryption" />
      <MemberSignature Language="VB.NET" Value="Public Property RequireEncryption As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.RequireEncryption : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.WindowsAzure.Storage.Table.TableRequestOptions.RequireEncryption" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.WindowsAzure.Storage.IRequestOptions.RequireEncryption</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt einen Wert anzugeben, ob die Daten geschrieben und gelesen werden, von der Clientbibliothek verschlüsselt werden sollen.
            </summary>
        <value>Verwendung <c>"true"</c> um anzugeben, dass die Daten werden soll, für alle Transaktionen verschlüsselt und entschlüsselt, und andernfalls <c>"false"</c>.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RetryPolicy">
      <MemberSignature Language="C#" Value="public Microsoft.WindowsAzure.Storage.RetryPolicies.IRetryPolicy RetryPolicy { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.WindowsAzure.Storage.RetryPolicies.IRetryPolicy RetryPolicy" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.Table.TableRequestOptions.RetryPolicy" />
      <MemberSignature Language="VB.NET" Value="Public Property RetryPolicy As IRetryPolicy" />
      <MemberSignature Language="F#" Value="member this.RetryPolicy : Microsoft.WindowsAzure.Storage.RetryPolicies.IRetryPolicy with get, set" Usage="Microsoft.WindowsAzure.Storage.Table.TableRequestOptions.RetryPolicy" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.WindowsAzure.Storage.IRequestOptions.RetryPolicy</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.RetryPolicies.IRetryPolicy</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt die wiederholungsrichtlinie für die Anforderung.
            </summary>
        <value>Ein Objekt vom Typ <see cref="T:Microsoft.WindowsAzure.Storage.RetryPolicies.IRetryPolicy" />.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ServerTimeout">
      <MemberSignature Language="C#" Value="public Nullable&lt;TimeSpan&gt; ServerTimeout { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.TimeSpan&gt; ServerTimeout" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.Table.TableRequestOptions.ServerTimeout" />
      <MemberSignature Language="VB.NET" Value="Public Property ServerTimeout As Nullable(Of TimeSpan)" />
      <MemberSignature Language="F#" Value="member this.ServerTimeout : Nullable&lt;TimeSpan&gt; with get, set" Usage="Microsoft.WindowsAzure.Storage.Table.TableRequestOptions.ServerTimeout" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.WindowsAzure.Storage.IRequestOptions.ServerTimeout</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.TimeSpan&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt sie fest das Timeoutintervall für die Anforderung.
            </summary>
        <value>Ein <see cref="T:System.TimeSpan" /> mit dem servertimeoutintervall für die Anforderung.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>