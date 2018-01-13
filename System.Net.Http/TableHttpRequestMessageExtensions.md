<Type Name="TableHttpRequestMessageExtensions" FullName="System.Net.Http.TableHttpRequestMessageExtensions">
  <TypeSignature Language="C#" Value="public static class TableHttpRequestMessageExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit TableHttpRequestMessageExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:System.Net.Http.TableHttpRequestMessageExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module TableHttpRequestMessageExtensions" />
  <TypeSignature Language="F#" Value="type TableHttpRequestMessageExtensions = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Mobile.Server.Tables</AssemblyName>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>System.ComponentModel.EditorBrowsable(System.ComponentModel.EditorBrowsableState.Never)</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            Erweiterungsmethoden für die <see cref="T:System.Net.Http.HttpRequestMessage" /> Klasse, die Entwicklung von Funktionen, die im Zusammenhang mit der Tabelle <see cref="T:Microsoft.Azure.Mobile.Server.TableController`1" />.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="AreDeletedRowsRequested">
      <MemberSignature Language="C#" Value="public static bool AreDeletedRowsRequested (this System.Net.Http.HttpRequestMessage request);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig bool AreDeletedRowsRequested(class System.Net.Http.HttpRequestMessage request) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Net.Http.TableHttpRequestMessageExtensions.AreDeletedRowsRequested(System.Net.Http.HttpRequestMessage)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function AreDeletedRowsRequested (request As HttpRequestMessage) As Boolean" />
      <MemberSignature Language="F#" Value="static member AreDeletedRowsRequested : System.Net.Http.HttpRequestMessage -&gt; bool" Usage="System.Net.Http.TableHttpRequestMessageExtensions.AreDeletedRowsRequested request" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Server.Tables</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="request" Type="System.Net.Http.HttpRequestMessage" RefType="this" />
      </Parameters>
      <Docs>
        <param name="request">Die <see cref="T:System.Net.Http.HttpRequestMessage" />Anforderung</param>
        <summary>
            Bestimmt, ob die gelöschte Zeilen vom Client angefordert wurden.
            </summary>
        <returns>"True", wenn die gelöschten Zeilen angefordert, andernfalls "false werden".</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetVersionFromIfMatch">
      <MemberSignature Language="C#" Value="public static byte[] GetVersionFromIfMatch (this System.Net.Http.HttpRequestMessage request);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig unsigned int8[] GetVersionFromIfMatch(class System.Net.Http.HttpRequestMessage request) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Net.Http.TableHttpRequestMessageExtensions.GetVersionFromIfMatch(System.Net.Http.HttpRequestMessage)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function GetVersionFromIfMatch (request As HttpRequestMessage) As Byte()" />
      <MemberSignature Language="F#" Value="static member GetVersionFromIfMatch : System.Net.Http.HttpRequestMessage -&gt; byte[]" Usage="System.Net.Http.TableHttpRequestMessageExtensions.GetVersionFromIfMatch request" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Server.Tables</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Diagnostics.CodeAnalysis.SuppressMessage("Microsoft.Reliability", "CA2000:Dispose objects before losing scope", Justification="Response is disposed by caller.")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Byte[]</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="request" Type="System.Net.Http.HttpRequestMessage" RefType="this" />
      </Parameters>
      <Docs>
        <param name="request"></param>
        <summary>
            Ruft die Version eines Elements für die Tabelle aus dem HTTP- <c>IfMatch</c> Header. Wenn die <c>IfMatch</c> enthält einen ungültigen Wert ein <see cref="T:System.Web.Http.HttpResponseException" /> wird ausgelöst, die eine <see cref="T:System.Net.Http.HttpResponseMessage" /> mit dem Statuscode <see cref="F:System.Net.HttpStatusCode.BadRequest" />.
            </summary>
        <returns>Eine gültige Version-Byte-Array, das die Version darstellt oder <c>null</c> , wenn keine vorhanden waren.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SetSelectedProperties">
      <MemberSignature Language="C#" Value="public static System.Collections.Generic.IList&lt;string&gt; SetSelectedProperties (this System.Net.Http.HttpRequestMessage request, Type data, out bool isModified);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Collections.Generic.IList`1&lt;string&gt; SetSelectedProperties(class System.Net.Http.HttpRequestMessage request, class System.Type data, [out] bool&amp; isModified) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Net.Http.TableHttpRequestMessageExtensions.SetSelectedProperties(System.Net.Http.HttpRequestMessage,System.Type,System.Boolean@)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function SetSelectedProperties (request As HttpRequestMessage, data As Type, ByRef isModified As Boolean) As IList(Of String)" />
      <MemberSignature Language="F#" Value="static member SetSelectedProperties : System.Net.Http.HttpRequestMessage * Type *  -&gt; System.Collections.Generic.IList&lt;string&gt;" Usage="System.Net.Http.TableHttpRequestMessageExtensions.SetSelectedProperties (request, data, isModified)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Server.Tables</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Diagnostics.CodeAnalysis.SuppressMessage("Microsoft.Design", "CA1021:AvoidOutParameters", Justification="It's ok to have an out parameter here.")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;System.String&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="request" Type="System.Net.Http.HttpRequestMessage" RefType="this" />
        <Parameter Name="data" Type="System.Type" />
        <Parameter Name="isModified" Type="System.Boolean&amp;" RefType="out" />
      </Parameters>
      <Docs>
        <param name="request">Die <see cref="T:System.Net.Http.HttpRequestMessage" />Anforderung</param>
        <param name="data">Der Typ des Datenmodells.</param>
        <param name="isModified">Gibt an, ob die ursprüngliche Anforderungs-URI $select-Klausel oder nicht manipuliert wurde.</param>
        <summary>
            Bestimmt den Satz von Eigenschaften einschließt, die Abfrageoption von OData $select für Typen implementieren die <see cref="T:Microsoft.Azure.Mobile.Server.Tables.ITableData" /> Schnittstelle. Diese Funktion legt fest, die der ausgewählten Eigenschaften und im Anforderungs-URI entsprechend aktualisiert, falls erforderlich.
            </summary>
        <returns>Entspricht ein Typ implementieren, der Satz von ausgewählten Eigenschaften; andernfalls Null.</returns>
        <remarks>Die Abfrage wird nicht tatsächlich überprüft in diesem Schritt – in diesem Fall als Teil der <see cref="T:System.Web.Http.QueryableAttribute" /> Überprüfung.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SetSelectedProperties">
      <MemberSignature Language="C#" Value="public static System.Collections.Generic.IList&lt;string&gt; SetSelectedProperties (this System.Net.Http.HttpRequestMessage request, Type data, System.Collections.Generic.IDictionary&lt;string,string&gt; systemPropertyMap, out bool isModified);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Collections.Generic.IList`1&lt;string&gt; SetSelectedProperties(class System.Net.Http.HttpRequestMessage request, class System.Type data, class System.Collections.Generic.IDictionary`2&lt;string, string&gt; systemPropertyMap, [out] bool&amp; isModified) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Net.Http.TableHttpRequestMessageExtensions.SetSelectedProperties(System.Net.Http.HttpRequestMessage,System.Type,System.Collections.Generic.IDictionary{System.String,System.String},System.Boolean@)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function SetSelectedProperties (request As HttpRequestMessage, data As Type, systemPropertyMap As IDictionary(Of String, String), ByRef isModified As Boolean) As IList(Of String)" />
      <MemberSignature Language="F#" Value="static member SetSelectedProperties : System.Net.Http.HttpRequestMessage * Type * System.Collections.Generic.IDictionary&lt;string, string&gt; *  -&gt; System.Collections.Generic.IList&lt;string&gt;" Usage="System.Net.Http.TableHttpRequestMessageExtensions.SetSelectedProperties (request, data, systemPropertyMap, isModified)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Server.Tables</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Diagnostics.CodeAnalysis.SuppressMessage("Microsoft.Design", "CA1021:AvoidOutParameters", Justification="It's ok to have an out parameter here.")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;System.String&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="request" Type="System.Net.Http.HttpRequestMessage" RefType="this" />
        <Parameter Name="data" Type="System.Type" />
        <Parameter Name="systemPropertyMap" Type="System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;" />
        <Parameter Name="isModified" Type="System.Boolean&amp;" RefType="out" />
      </Parameters>
      <Docs>
        <param name="request">Die <see cref="T:System.Net.Http.HttpRequestMessage" />Anforderung</param>
        <param name="data">Der Typ des Datenmodells.</param>
        <param name="systemPropertyMap">Optionale Karte Ersatz-Namen für Systemeigenschaften angeben.</param>
        <param name="isModified">Gibt an, ob die ursprüngliche Anforderungs-URI $select-Klausel oder nicht manipuliert wurde.</param>
        <summary>
            Bestimmt den Satz von Eigenschaften einschließt, die Abfrageoption von OData $select für Typen implementieren die <see cref="T:Microsoft.Azure.Mobile.Server.Tables.ITableData" /> Schnittstelle. Diese Funktion legt fest, die Kombination der ausgewählten Eigenschaften und im Anforderungs-URI entsprechend aktualisiert, falls erforderlich.
            </summary>
        <returns>Entspricht ein Typ implementieren, der Satz von ausgewählten Eigenschaften; andernfalls Null.</returns>
        <remarks>Die Abfrage wird nicht tatsächlich überprüft in diesem Schritt – in diesem Fall als Teil der <see cref="T:System.Web.Http.QueryableAttribute" /> Überprüfung.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>