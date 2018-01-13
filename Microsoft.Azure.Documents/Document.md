<Type Name="Document" FullName="Microsoft.Azure.Documents.Document">
  <TypeSignature Language="C#" Value="public class Document : Microsoft.Azure.Documents.Resource, System.Dynamic.IDynamicMetaObjectProvider" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit Document extends Microsoft.Azure.Documents.Resource implements class System.Dynamic.IDynamicMetaObjectProvider" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Documents.Document" />
  <TypeSignature Language="VB.NET" Value="Public Class Document&#xA;Inherits Resource&#xA;Implements IDynamicMetaObjectProvider" />
  <TypeSignature Language="F#" Value="type Document = class&#xA;    inherit Resource&#xA;    interface IDynamicMetaObjectProvider" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.DocumentDB.Core</AssemblyName>
    <AssemblyVersion>1.6.0.0</AssemblyVersion>
    <AssemblyVersion>1.7.0.0</AssemblyVersion>
    <AssemblyVersion>1.7.1.0</AssemblyVersion>
  </AssemblyInfo>
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Documents.Client</AssemblyName>
    <AssemblyVersion>1.18.0.0</AssemblyVersion>
    <AssemblyVersion>1.19.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Documents.Resource</BaseTypeName>
  </Base>
  <Interfaces>
    <Interface>
      <InterfaceName>System.Dynamic.IDynamicMetaObjectProvider</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <summary>
            Stellt ein Dokument in der Azure-Cosmos-DB-Dienst dar.
            </summary>
    <remarks> 
            Ein Dokument ist eine strukturierte JSON-Dokument. Es gibt kein Schema Satz für die JSON-Dokumente, und ein Dokument kann eine beliebige Anzahl von benutzerdefinierten Eigenschaften sowie eine optionale Liste von Anlagen enthalten. Dokument ist eine Anwendungsressource und mit dem Hauptschlüssel oder / / Ressourcenschlüssel autorisiert werden kann.
            </remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public Document ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.Document.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DocumentDB.Core</AssemblyName>
        <AssemblyVersion>1.6.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.1.0</AssemblyVersion>
      </AssemblyInfo>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Documents.Client</AssemblyName>
        <AssemblyVersion>1.18.0.0</AssemblyVersion>
        <AssemblyVersion>1.19.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            Initialisiert eine neue Instanz der dem <see cref="T:Microsoft.Azure.Documents.Document" /> Klasse für den Azure-Cosmos-DB-Dienst.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AttachmentsLink">
      <MemberSignature Language="C#" Value="public string AttachmentsLink { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string AttachmentsLink" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Documents.Document.AttachmentsLink" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property AttachmentsLink As String" />
      <MemberSignature Language="F#" Value="member this.AttachmentsLink : string" Usage="Microsoft.Azure.Documents.Document.AttachmentsLink" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DocumentDB.Core</AssemblyName>
        <AssemblyVersion>1.6.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.1.0</AssemblyVersion>
      </AssemblyInfo>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Documents.Client</AssemblyName>
        <AssemblyVersion>1.18.0.0</AssemblyVersion>
        <AssemblyVersion>1.19.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab, der Self-link entsprechenden Anlagen des Dokuments aus dem Azure-Cosmos-DB-Dienst.
            </summary>
        <value>
            Die Self-link, entspricht die Anlagen des Dokuments.
            </value>
        <remarks>
            Jedes Dokument kann zwischen 0 (null) und viele Anhänge aufweisen. Der Anlagen-Link enthält einen Feed von Anlagen, die auf das Dokument gehören.
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="System.Dynamic.IDynamicMetaObjectProvider.GetMetaObject">
      <MemberSignature Language="C#" Value="System.Dynamic.DynamicMetaObject IDynamicMetaObjectProvider.GetMetaObject (System.Linq.Expressions.Expression parameter);" />
      <MemberSignature Language="ILAsm" Value=".method hidebysig newslot virtual instance class System.Dynamic.DynamicMetaObject System.Dynamic.IDynamicMetaObjectProvider.GetMetaObject(class System.Linq.Expressions.Expression parameter) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.Document.System#Dynamic#IDynamicMetaObjectProvider#GetMetaObject(System.Linq.Expressions.Expression)" />
      <MemberSignature Language="VB.NET" Value="Function GetMetaObject (parameter As Expression) As DynamicMetaObject Implements IDynamicMetaObjectProvider.GetMetaObject" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:System.Dynamic.IDynamicMetaObjectProvider.GetMetaObject(System.Linq.Expressions.Expression)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DocumentDB.Core</AssemblyName>
        <AssemblyVersion>1.6.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.1.0</AssemblyVersion>
      </AssemblyInfo>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Documents.Client</AssemblyName>
        <AssemblyVersion>1.18.0.0</AssemblyVersion>
        <AssemblyVersion>1.19.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Dynamic.DynamicMetaObject</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="parameter" Type="System.Linq.Expressions.Expression" />
      </Parameters>
      <Docs>
        <param name="parameter">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TimeToLive">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; TimeToLive { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; TimeToLive" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Documents.Document.TimeToLive" />
      <MemberSignature Language="VB.NET" Value="Public Property TimeToLive As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.TimeToLive : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Documents.Document.TimeToLive" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DocumentDB.Core</AssemblyName>
        <AssemblyVersion>1.6.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.1.0</AssemblyVersion>
      </AssemblyInfo>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Documents.Client</AssemblyName>
        <AssemblyVersion>1.18.0.0</AssemblyVersion>
        <AssemblyVersion>1.19.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(NullValueHandling=Newtonsoft.Json.NullValueHandling.Ignore, PropertyName="ttl")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt die Zeit in Sekunden für das Dokument in der Azure-Cosmos-DB-Dienst Gültigkeitsdauer fest.
            </summary>
        <value>
            Es ist eine optionale Eigenschaft. Ein gültiger Wert muss entweder eine positive ganze Zahl ungleich NULL, "1", oder <c>null</c>.
            Standardmäßig TimeToLive festgelegt ist, um null Bedeutung des Dokuments erbt der Auflistung <see cref="P:Microsoft.Azure.Documents.DocumentCollection.DefaultTimeToLive" />.
            Die Maßeinheit ist Sekunden. Die zulässige Maximalwert ist 2147483647.
            Der Wert "-1" ist, bedeutet dies nie ablaufen sollen, unabhängig von der Auflistung <see cref="P:Microsoft.Azure.Documents.DocumentCollection.DefaultTimeToLive" /> Wert.
            </value>
        <remarks>
          <para>
            Die endgültige Time-to-live-Richtlinie eines Dokuments nach Rücksprache mit der Auflistung überprüft <see cref="P:Microsoft.Azure.Documents.DocumentCollection.DefaultTimeToLive" />.
            </para>
          <para>
            Wenn die <see cref="P:Microsoft.Azure.Documents.Document.TimeToLive" /> ist <c>null</c>, erbt der Auflistung das Dokument <see cref="P:Microsoft.Azure.Documents.DocumentCollection.DefaultTimeToLive" />.
            Wenn der Auflistung <see cref="P:Microsoft.Azure.Documents.DocumentCollection.DefaultTimeToLive" /> ist eine positive ganze Zahl ungleich NULL, und klicken Sie dann das Dokument diesen Wert als seine-Gültigkeitsdauer in Sekunden übernimmt, und nach dem Standardverhalten Gültigkeitsdauer in Sekunden abgelaufen wird, seit der letzten Schreibzugriffs. Im Hintergrund werden die abgelaufenen Dokumente gelöscht.
            Andernfalls wird das Dokument nie ablaufen.
            </para>
          <para>
            Wenn die <see cref="P:Microsoft.Azure.Documents.Document.TimeToLive" /> ist "1", das Dokument wird nie ablaufen, unabhängig von der Auflistung <see cref="P:Microsoft.Azure.Documents.DocumentCollection.DefaultTimeToLive" /> Wert.
            </para>
          <para>
            Wenn die <see cref="P:Microsoft.Azure.Documents.Document.TimeToLive" /> ist eine positive ganze Zahl ungleich NULL, überprüfen Sie die Auflistung müssen <see cref="P:Microsoft.Azure.Documents.DocumentCollection.DefaultTimeToLive" />.
            Wenn der Auflistung <see cref="P:Microsoft.Azure.Documents.DocumentCollection.DefaultTimeToLive" /> ist <c>null</c>, d. h. die Time-to-live wurde deaktiviert, auf die Sammlung und des Dokuments <see cref="P:Microsoft.Azure.Documents.Document.TimeToLive" /> nicht berücksichtigt werden sollten und das Dokument nicht abläuft.
            Andernfalls des Dokuments <see cref="P:Microsoft.Azure.Documents.Document.TimeToLive" /> wird berücksichtigt werden. Das Dokument wird nach dem Standardverhalten Gültigkeitsdauer in Sekunden, seit der letzten Schreibzugriffs abgelaufen sein. Im Hintergrund werden die abgelaufenen Dokumente gelöscht.
            </para>
          <para>
            Folgende Tabelle zeigt ein Beispiel für die Matrix die endgültigen Time-to-live-Richtlinie mit einem Collection auszuwerten <see cref="P:Microsoft.Azure.Documents.DocumentCollection.DefaultTimeToLive" /> und ein Dokument <see cref="P:Microsoft.Azure.Documents.Document.TimeToLive" />.
            </para>
          <list type="table">
            <listheader>
              <term>Sammlung</term>
              <description>Matrix</description>
            </listheader>
            <item>
              <term>DefaultTimeToLive = Null</term>
              <description>
                <list type="table">
                  <listheader>
                    <term>Dokument</term>
                    <description>Ergebnis</description>
                  </listheader>
                  <item>
                    <term>TimeToLive = Null</term>
                    <description>Gültigkeitsdauer (TTL) ist deaktiviert. Das Dokument läuft nie ab (Standard).</description>
                  </item>
                  <item>
                    <term>TimeToLive =-1</term>
                    <description>Gültigkeitsdauer (TTL) ist deaktiviert. Das Dokument abläuft nicht.</description>
                  </item>
                  <item>
                    <term>TimeToLive = 2000</term>
                    <description>Gültigkeitsdauer (TTL) ist deaktiviert. Das Dokument abläuft nicht.</description>
                  </item>
                </list>
              </description>
            </item>
            <item>
              <term>DefaultTimeToLive =-1</term>
              <description>
                <list type="table">
                  <listheader>
                    <term>Dokument</term>
                    <description>Ergebnis</description>
                  </listheader>
                  <item>
                    <term>TimeToLive = Null</term>
                    <description>Gültigkeitsdauer (TTL) aktiviert ist. Das Dokument läuft nie ab (Standard).</description>
                  </item>
                  <item>
                    <term>TimeToLive =-1</term>
                    <description>Gültigkeitsdauer (TTL) aktiviert ist. Das Dokument abläuft nicht.</description>
                  </item>
                  <item>
                    <term>TimeToLive = 2000</term>
                    <description>Gültigkeitsdauer (TTL) aktiviert ist. Das Dokument läuft nach 2000 Sekunden.</description>
                  </item>
                </list>
              </description>
            </item>
            <item>
              <term>DefaultTimeToLive = 1000</term>
              <description>
                <list type="table">
                  <listheader>
                    <term>Dokument</term>
                    <description>Ergebnis</description>
                  </listheader>
                  <item>
                    <term>TimeToLive = Null</term>
                    <description>Gültigkeitsdauer (TTL) aktiviert ist. Das Dokument läuft nach 1000 Sekunden (Standard).</description>
                  </item>
                  <item>
                    <term>TimeToLive =-1</term>
                    <description>Gültigkeitsdauer (TTL) aktiviert ist. Das Dokument abläuft nicht.</description>
                  </item>
                  <item>
                    <term>TimeToLive = 2000</term>
                    <description>Gültigkeitsdauer (TTL) aktiviert ist. Das Dokument läuft nach 2000 Sekunden.</description>
                  </item>
                </list>
              </description>
            </item>
          </list>
        </remarks>
        <altmember cref="T:Microsoft.Azure.Documents.DocumentCollection" />
        <example>
            Im folgenden Beispiel entfernt "Ttl" aus dem Inhalt des Dokuments.
            Das Dokument wird der Auflistung erben <see cref="P:Microsoft.Azure.Documents.DocumentCollection.DefaultTimeToLive" /> als Time-to-live Wert.
            <code language="c#"><![CDATA[
                document.TimeToLive = null;
            ]]></code></example>
        <example>
            Im folgenden Beispiel wird sichergestellt, dass das Dokument unabhängig davon nie ablaufen sollen.
            <code language="c#"><![CDATA[
                document.TimeToLive = -1;
            ]]></code></example>
        <example>
            Das folgende Beispiel legt die Time-to-live in Sekunden für ein Dokument fest.
            Das Dokument läuft nach 1000 Sekunden seit seiner letzten Schreibvorgang, wenn Zeit der Auflistung <see cref="P:Microsoft.Azure.Documents.DocumentCollection.DefaultTimeToLive" /> nicht <c>null</c>.
            <code language="c#"><![CDATA[
            document.TimeToLive = 1000;
                ]]></code></example>
      </Docs>
    </Member>
  </Members>
</Type>