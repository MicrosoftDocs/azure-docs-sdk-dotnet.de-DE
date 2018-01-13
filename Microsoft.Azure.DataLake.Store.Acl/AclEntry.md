<Type Name="AclEntry" FullName="Microsoft.Azure.DataLake.Store.Acl.AclEntry">
  <TypeSignature Language="C#" Value="public class AclEntry" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit AclEntry extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.DataLake.Store.Acl.AclEntry" />
  <TypeSignature Language="VB.NET" Value="Public Class AclEntry" />
  <TypeSignature Language="F#" Value="type AclEntry = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.DataLake.Store</AssemblyName>
    <AssemblyVersion>0.1.0.0</AssemblyVersion>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>To be added.</summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public AclEntry (Microsoft.Azure.DataLake.Store.Acl.AclType type, string userOrGroupId, Microsoft.Azure.DataLake.Store.Acl.AclScope scope, Microsoft.Azure.DataLake.Store.Acl.AclAction action);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(valuetype Microsoft.Azure.DataLake.Store.Acl.AclType type, string userOrGroupId, valuetype Microsoft.Azure.DataLake.Store.Acl.AclScope scope, valuetype Microsoft.Azure.DataLake.Store.Acl.AclAction action) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.DataLake.Store.Acl.AclEntry.#ctor(Microsoft.Azure.DataLake.Store.Acl.AclType,System.String,Microsoft.Azure.DataLake.Store.Acl.AclScope,Microsoft.Azure.DataLake.Store.Acl.AclAction)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (type As AclType, userOrGroupId As String, scope As AclScope, action As AclAction)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.DataLake.Store.Acl.AclEntry : Microsoft.Azure.DataLake.Store.Acl.AclType * string * Microsoft.Azure.DataLake.Store.Acl.AclScope * Microsoft.Azure.DataLake.Store.Acl.AclAction -&gt; Microsoft.Azure.DataLake.Store.Acl.AclEntry" Usage="new Microsoft.Azure.DataLake.Store.Acl.AclEntry (type, userOrGroupId, scope, action)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DataLake.Store</AssemblyName>
        <AssemblyVersion>0.1.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="type" Type="Microsoft.Azure.DataLake.Store.Acl.AclType" />
        <Parameter Name="userOrGroupId" Type="System.String" />
        <Parameter Name="scope" Type="Microsoft.Azure.DataLake.Store.Acl.AclScope" />
        <Parameter Name="action" Type="Microsoft.Azure.DataLake.Store.Acl.AclAction" />
      </Parameters>
      <Docs>
        <param name="type">Art des ACL-Eintrags: Benutzer/Gruppe/andere/Maske</param>
        <param name="userOrGroupId">Objekt-ID des Objekts je nach Art des ACL-Eintrags. Andere Acl Typ und Maske sollte null sein</param>
        <param name="scope">Zugriff oder DEFAULT</param>
        <param name="action">Der Typ des ACL festlegen</param>
        <summary>
            Öffentlicher Konstruktor
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Action">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.DataLake.Store.Acl.AclAction Action { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.Azure.DataLake.Store.Acl.AclAction Action" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.DataLake.Store.Acl.AclEntry.Action" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Action As AclAction" />
      <MemberSignature Language="F#" Value="member this.Action : Microsoft.Azure.DataLake.Store.Acl.AclAction" Usage="Microsoft.Azure.DataLake.Store.Acl.AclEntry.Action" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DataLake.Store</AssemblyName>
        <AssemblyVersion>0.1.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.DataLake.Store.Acl.AclAction</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Der Typ des ACL festlegen
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Equals">
      <MemberSignature Language="C#" Value="public bool Equals (Microsoft.Azure.DataLake.Store.Acl.AclEntry entry);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance bool Equals(class Microsoft.Azure.DataLake.Store.Acl.AclEntry entry) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.DataLake.Store.Acl.AclEntry.Equals(Microsoft.Azure.DataLake.Store.Acl.AclEntry)" />
      <MemberSignature Language="VB.NET" Value="Public Function Equals (entry As AclEntry) As Boolean" />
      <MemberSignature Language="F#" Value="override this.Equals : Microsoft.Azure.DataLake.Store.Acl.AclEntry -&gt; bool" Usage="aclEntry.Equals entry" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DataLake.Store</AssemblyName>
        <AssemblyVersion>0.1.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="entry" Type="Microsoft.Azure.DataLake.Store.Acl.AclEntry" />
      </Parameters>
      <Docs>
        <param name="entry">ACL-Eintrag</param>
        <summary>
            Gibt "true" zurück, wenn der Typ, Typnamen, Bereich und Aktion alle denselben sind
            </summary>
        <returns>True, wenn die Acl-Einträge entspricht, andernfalls "false" werden</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Equals">
      <MemberSignature Language="C#" Value="public override bool Equals (object obj);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance bool Equals(object obj) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.DataLake.Store.Acl.AclEntry.Equals(System.Object)" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function Equals (obj As Object) As Boolean" />
      <MemberSignature Language="F#" Value="override this.Equals : obj -&gt; bool" Usage="aclEntry.Equals obj" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DataLake.Store</AssemblyName>
        <AssemblyVersion>0.1.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="obj" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="obj">ACL-Eintrag</param>
        <summary>
            Gibt "true" zurück, wenn der Typ, Typnamen, Bereich und Aktion alle denselben sind
            </summary>
        <returns>True, wenn AclEntries gleichen andernfalls "false"</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ParseAclEntriesString">
      <MemberSignature Language="C#" Value="public static System.Collections.Generic.List&lt;Microsoft.Azure.DataLake.Store.Acl.AclEntry&gt; ParseAclEntriesString (string aclEntries);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Collections.Generic.List`1&lt;class Microsoft.Azure.DataLake.Store.Acl.AclEntry&gt; ParseAclEntriesString(string aclEntries) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.DataLake.Store.Acl.AclEntry.ParseAclEntriesString(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function ParseAclEntriesString (aclEntries As String) As List(Of AclEntry)" />
      <MemberSignature Language="F#" Value="static member ParseAclEntriesString : string -&gt; System.Collections.Generic.List&lt;Microsoft.Azure.DataLake.Store.Acl.AclEntry&gt;" Usage="Microsoft.Azure.DataLake.Store.Acl.AclEntry.ParseAclEntriesString aclEntries" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DataLake.Store</AssemblyName>
        <AssemblyVersion>0.1.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.List&lt;Microsoft.Azure.DataLake.Store.Acl.AclEntry&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="aclEntries" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="aclEntries">Zeichenfolge, enthält jeder Eintrag als Trennzeichen dienen die Acl-Einträge ","</param>
        <summary>
            Analysiert die Zeichenfolge jedes Acl-Eintrag, und klicken Sie dann liefert eine Liste aller Acl-Einträge
            </summary>
        <returns>Liste der Acl-Einträge</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ParseAclEntryString">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.DataLake.Store.Acl.AclEntry ParseAclEntryString (string aclEntry, bool removeAcl);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.DataLake.Store.Acl.AclEntry ParseAclEntryString(string aclEntry, bool removeAcl) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.DataLake.Store.Acl.AclEntry.ParseAclEntryString(System.String,System.Boolean)" />
      <MemberSignature Language="F#" Value="static member ParseAclEntryString : string * bool -&gt; Microsoft.Azure.DataLake.Store.Acl.AclEntry" Usage="Microsoft.Azure.DataLake.Store.Acl.AclEntry.ParseAclEntryString (aclEntry, removeAcl)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DataLake.Store</AssemblyName>
        <AssemblyVersion>0.1.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.DataLake.Store.Acl.AclEntry</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="aclEntry" Type="System.String" />
        <Parameter Name="removeAcl" Type="System.Boolean" />
      </Parameters>
      <Docs>
        <param name="aclEntry">ACL-Eintrag-Zeichenfolge, die getrennt durch ":"</param>
        <param name="removeAcl">Gibt an, ob diese Zeichenfolge ist für die Acl entfernt.</param>
        <summary>
            Analysiert eine Zeichenfolge AclEntry in Acl-Typ, Acl-Typ-Id, Bereich Acl und Acl-Aktion (Berechtigungen).
            Löst die Ausnahme aus, wenn die Acl-Zeichenfolge nicht korrekt ist.
            </summary>
        <returns>ACL-Eintrag-Instanz</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Scope">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.DataLake.Store.Acl.AclScope Scope { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.Azure.DataLake.Store.Acl.AclScope Scope" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.DataLake.Store.Acl.AclEntry.Scope" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Scope As AclScope" />
      <MemberSignature Language="F#" Value="member this.Scope : Microsoft.Azure.DataLake.Store.Acl.AclScope" Usage="Microsoft.Azure.DataLake.Store.Acl.AclEntry.Scope" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DataLake.Store</AssemblyName>
        <AssemblyVersion>0.1.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.DataLake.Store.Acl.AclScope</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Zugriff oder DEFAULT
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SerializeAcl">
      <MemberSignature Language="C#" Value="public static string SerializeAcl (System.Collections.Generic.List&lt;Microsoft.Azure.DataLake.Store.Acl.AclEntry&gt; aclList, bool removeAcl);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig string SerializeAcl(class System.Collections.Generic.List`1&lt;class Microsoft.Azure.DataLake.Store.Acl.AclEntry&gt; aclList, bool removeAcl) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.DataLake.Store.Acl.AclEntry.SerializeAcl(System.Collections.Generic.List{Microsoft.Azure.DataLake.Store.Acl.AclEntry},System.Boolean)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function SerializeAcl (aclList As List(Of AclEntry), removeAcl As Boolean) As String" />
      <MemberSignature Language="F#" Value="static member SerializeAcl : System.Collections.Generic.List&lt;Microsoft.Azure.DataLake.Store.Acl.AclEntry&gt; * bool -&gt; string" Usage="Microsoft.Azure.DataLake.Store.Acl.AclEntry.SerializeAcl (aclList, removeAcl)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DataLake.Store</AssemblyName>
        <AssemblyVersion>0.1.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="aclList" Type="System.Collections.Generic.List&lt;Microsoft.Azure.DataLake.Store.Acl.AclEntry&gt;" />
        <Parameter Name="removeAcl" Type="System.Boolean" />
      </Parameters>
      <Docs>
        <param name="aclList">Liste der ACL-Einträge</param>
        <param name="removeAcl">True, wenn Sie aufgerufen wird, beim Entfernen von Zugriffssteuerungslisten</param>
        <summary>
            Serialisiert die ACL-Einträge aus einer Liste von ACL-Einträge in einer Zeichenfolge
            </summary>
        <returns>Liste der Acl-Einträge, die in ein Zeichenfolgenformat jeder Eintrag als Trennzeichen verkettet ","</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ToString">
      <MemberSignature Language="C#" Value="public override string ToString ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance string ToString() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.DataLake.Store.Acl.AclEntry.ToString" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function ToString () As String" />
      <MemberSignature Language="F#" Value="override this.ToString : unit -&gt; string" Usage="aclEntry.ToString " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DataLake.Store</AssemblyName>
        <AssemblyVersion>0.1.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ToString">
      <MemberSignature Language="C#" Value="public string ToString (bool removeAcl);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance string ToString(bool removeAcl) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.DataLake.Store.Acl.AclEntry.ToString(System.Boolean)" />
      <MemberSignature Language="VB.NET" Value="Public Function ToString (removeAcl As Boolean) As String" />
      <MemberSignature Language="F#" Value="override this.ToString : bool -&gt; string" Usage="aclEntry.ToString removeAcl" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DataLake.Store</AssemblyName>
        <AssemblyVersion>0.1.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="removeAcl" Type="System.Boolean" />
      </Parameters>
      <Docs>
        <param name="removeAcl">True, wenn Sie aufgerufen wird, beim Entfernen von Zugriffssteuerungslisten</param>
        <summary>
            Gibt das Zeichenfolgenformat jedes ACL-Eintrags
            </summary>
        <returns>ACL-Eintrag in ein Zeichenfolgenformat, wobei jeder Teil als Trennzeichen dienen die ":"</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Type">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.DataLake.Store.Acl.AclType Type { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.Azure.DataLake.Store.Acl.AclType Type" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.DataLake.Store.Acl.AclEntry.Type" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Type As AclType" />
      <MemberSignature Language="F#" Value="member this.Type : Microsoft.Azure.DataLake.Store.Acl.AclType" Usage="Microsoft.Azure.DataLake.Store.Acl.AclEntry.Type" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DataLake.Store</AssemblyName>
        <AssemblyVersion>0.1.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.DataLake.Store.Acl.AclType</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Art des ACL-Eintrags: Benutzer/Gruppe/andere/Maske
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UserOrGroupId">
      <MemberSignature Language="C#" Value="public string UserOrGroupId { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string UserOrGroupId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.DataLake.Store.Acl.AclEntry.UserOrGroupId" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property UserOrGroupId As String" />
      <MemberSignature Language="F#" Value="member this.UserOrGroupId : string" Usage="Microsoft.Azure.DataLake.Store.Acl.AclEntry.UserOrGroupId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DataLake.Store</AssemblyName>
        <AssemblyVersion>0.1.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            ObjectID des Objekts, je nach Art des ACL-Eintrags
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>