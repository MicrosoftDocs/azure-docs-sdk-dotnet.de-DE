<Type Name="JsonWebKeyVerifier" FullName="Microsoft.Azure.KeyVault.WebKey.JsonWebKeyVerifier">
  <TypeSignature Language="C#" Value="public abstract class JsonWebKeyVerifier" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract beforefieldinit JsonWebKeyVerifier extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.KeyVault.WebKey.JsonWebKeyVerifier" />
  <TypeSignature Language="VB.NET" Value="Public MustInherit Class JsonWebKeyVerifier" />
  <TypeSignature Language="F#" Value="type JsonWebKeyVerifier = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.KeyVault.WebKey</AssemblyName>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            Eine Klasse, die überprüft, Instanzen von ob <see cref="T:Microsoft.Azure.KeyVault.WebKey.JsonWebKey" /> gemäß Schlüsseltyp. 
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="protected JsonWebKeyVerifier (string kty);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig specialname rtspecialname instance void .ctor(string kty) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.WebKey.JsonWebKeyVerifier.#ctor(System.String)" />
      <MemberSignature Language="VB.NET" Value="Protected Sub New (kty As String)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.KeyVault.WebKey.JsonWebKeyVerifier : string -&gt; Microsoft.Azure.KeyVault.WebKey.JsonWebKeyVerifier" Usage="new Microsoft.Azure.KeyVault.WebKey.JsonWebKeyVerifier kty" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault.WebKey</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="kty" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="kty">Gibt an, welche Art von Schlüssel für diese Prüfung gilt.</param>
        <summary>
            Initialisiert eine neue Instanz den angegebenen Wert festlegen, in der <see cref="P:Microsoft.Azure.KeyVault.WebKey.JsonWebKeyVerifier.Kty" /> Eigenschaft.
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentNullException">Wenn der angegebene Wert ist <code>null</code>, leer oder ein Leerzeichen.</exception>
        <exception cref="T:System.ArgumentException">Wenn der angegebene Wert ein ungültige Zeichen enthält.</exception>
      </Docs>
    </Member>
    <Member MemberName="AddCompatibleOperations">
      <MemberSignature Language="C#" Value="protected abstract void AddCompatibleOperations (System.Collections.Generic.ICollection&lt;string&gt; compatibleOperations);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig newslot virtual instance void AddCompatibleOperations(class System.Collections.Generic.ICollection`1&lt;string&gt; compatibleOperations) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.WebKey.JsonWebKeyVerifier.AddCompatibleOperations(System.Collections.Generic.ICollection{System.String})" />
      <MemberSignature Language="VB.NET" Value="Protected MustOverride Sub AddCompatibleOperations (compatibleOperations As ICollection(Of String))" />
      <MemberSignature Language="F#" Value="abstract member AddCompatibleOperations : System.Collections.Generic.ICollection&lt;string&gt; -&gt; unit" Usage="jsonWebKeyVerifier.AddCompatibleOperations compatibleOperations" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault.WebKey</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="compatibleOperations" Type="System.Collections.Generic.ICollection&lt;System.String&gt;" />
      </Parameters>
      <Docs>
        <param name="compatibleOperations">To be added.</param>
        <summary>
            Fügt der angegebenen Auflistung alle Vorgänge, die mit Schlüsseln erfolgen können, die von diesem Objekt, dessen Typ behandelt wird.
            </summary>
        <remarks>To be added.</remarks>
        <see cref="F:Microsoft.Azure.KeyVault.WebKey.JsonWebKeyOperation.Sign" />
        <see cref="F:Microsoft.Azure.KeyVault.WebKey.JsonWebKeyOperation.Verify" />
      </Docs>
    </Member>
    <Member MemberName="AddItem&lt;T&gt;">
      <MemberSignature Language="C#" Value="protected static void AddItem&lt;T&gt; (ref System.Collections.Generic.ICollection&lt;T&gt; items, T newItem);" />
      <MemberSignature Language="ILAsm" Value=".method familystatic hidebysig void AddItem&lt;T&gt;(class System.Collections.Generic.ICollection`1&lt;!!T&gt;&amp; items, !!T newItem) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.WebKey.JsonWebKeyVerifier.AddItem``1(System.Collections.Generic.ICollection{``0}@,``0)" />
      <MemberSignature Language="VB.NET" Value="Protected Shared Sub AddItem(Of T) (ByRef items As ICollection(Of T), newItem As T)" />
      <MemberSignature Language="F#" Value="static member AddItem :  * 'T -&gt; unit" Usage="Microsoft.Azure.KeyVault.WebKey.JsonWebKeyVerifier.AddItem (items, newItem)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault.WebKey</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <TypeParameters>
        <TypeParameter Name="T" />
      </TypeParameters>
      <Parameters>
        <Parameter Name="items" Type="System.Collections.Generic.ICollection&lt;T&gt;&amp;" RefType="ref" />
        <Parameter Name="newItem" Type="T" />
      </Parameters>
      <Docs>
        <typeparam name="T">To be added.</typeparam>
        <param name="items">To be added.</param>
        <param name="newItem">To be added.</param>
        <summary>
            Hilfsmethode, die den Vorgang zum Erstellen einer Sammlung (falls erforderlich) verknüpft und ein Element hinzugefügt wird.
            </summary>
        <remarks>To be added.</remarks>
        <see cref="T:System.Collections.Generic.List`1" />
      </Docs>
    </Member>
    <Member MemberName="AddUsedProperties">
      <MemberSignature Language="C#" Value="protected abstract void AddUsedProperties (System.Collections.Generic.ICollection&lt;string&gt; usedProperties);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig newslot virtual instance void AddUsedProperties(class System.Collections.Generic.ICollection`1&lt;string&gt; usedProperties) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.WebKey.JsonWebKeyVerifier.AddUsedProperties(System.Collections.Generic.ICollection{System.String})" />
      <MemberSignature Language="VB.NET" Value="Protected MustOverride Sub AddUsedProperties (usedProperties As ICollection(Of String))" />
      <MemberSignature Language="F#" Value="abstract member AddUsedProperties : System.Collections.Generic.ICollection&lt;string&gt; -&gt; unit" Usage="jsonWebKeyVerifier.AddUsedProperties usedProperties" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault.WebKey</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="usedProperties" Type="System.Collections.Generic.ICollection&lt;System.String&gt;" />
      </Parameters>
      <Docs>
        <param name="usedProperties">To be added.</param>
        <summary>
            Fügt der angegebenen Auflistung alle JsonWebKey-Eigenschaften, die Schlüssel sind von diesem Objekt, dessen Typ behandelt wird.
            </summary>
        <remarks>To be added.</remarks>
        <para>Diese Methode muss JSON-Eigenschaftennamen, hinzufügen, z. B. <code>"crv"</code>, <code>"p"</code>usw. C#-Eigenschaftennamen müssen nicht hinzugefügt.</para>
        <para>Diese Methode keinen hinzuzufügende <code>"kid"</code>, <code>"kty"</code> und <code>"key_ops"</code>.
            Es wird angenommen, dass Thesaurus-Eigenschaften für alle Schlüssel hilfreich sein.</para>
      </Docs>
    </Member>
    <Member MemberName="GetVerifier">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.KeyVault.WebKey.JsonWebKeyVerifier GetVerifier (string kty);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.KeyVault.WebKey.JsonWebKeyVerifier GetVerifier(string kty) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.WebKey.JsonWebKeyVerifier.GetVerifier(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function GetVerifier (kty As String) As JsonWebKeyVerifier" />
      <MemberSignature Language="F#" Value="static member GetVerifier : string -&gt; Microsoft.Azure.KeyVault.WebKey.JsonWebKeyVerifier" Usage="Microsoft.Azure.KeyVault.WebKey.JsonWebKeyVerifier.GetVerifier kty" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault.WebKey</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.KeyVault.WebKey.JsonWebKeyVerifier</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="kty" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="kty">To be added.</param>
        <summary>
            Gibt die Überprüfung zurück, registriert wird, damit der angegebene Kty-Wert oder null, wenn der Wert für Kty nicht registriert wurde.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <see cref="T:Microsoft.Azure.KeyVault.WebKey.JsonWebKeyType" />
        <altmember cref="M:Microsoft.Azure.KeyVault.WebKey.JsonWebKeyVerifier.Register(Microsoft.Azure.KeyVault.WebKey.JsonWebKeyVerifier)" />
      </Docs>
    </Member>
    <Member MemberName="HasSecretKey">
      <MemberSignature Language="C#" Value="public abstract bool HasSecretKey { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool HasSecretKey" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.KeyVault.WebKey.JsonWebKeyVerifier.HasSecretKey" />
      <MemberSignature Language="VB.NET" Value="Public MustOverride ReadOnly Property HasSecretKey As Boolean" />
      <MemberSignature Language="F#" Value="member this.HasSecretKey : bool" Usage="Microsoft.Azure.KeyVault.WebKey.JsonWebKeyVerifier.HasSecretKey" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault.WebKey</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Gibt an, ob der Typ des Schlüssels, der von diesem Objekt überprüft eine geheime Komponente wie eine Hardware-Schlüsseltoken enthält.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
        <code>true</code>
        <see cref="M:Microsoft.Azure.KeyVault.WebKey.JsonWebKeyVerifier.IsSecretKeyComplete(Microsoft.Azure.KeyVault.WebKey.JsonWebKey,System.Collections.Generic.ICollection{System.String}@)" />
        <see cref="M:Microsoft.Azure.KeyVault.WebKey.JsonWebKeyVerifier.IsSecretKeyValid(Microsoft.Azure.KeyVault.WebKey.JsonWebKey,System.String@)" />
      </Docs>
    </Member>
    <Member MemberName="IsAnyPrivateKeyParamSpecified">
      <MemberSignature Language="C#" Value="public virtual bool IsAnyPrivateKeyParamSpecified (Microsoft.Azure.KeyVault.WebKey.JsonWebKey webKey, ref System.Collections.Generic.ICollection&lt;string&gt; specifiedProps);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance bool IsAnyPrivateKeyParamSpecified(class Microsoft.Azure.KeyVault.WebKey.JsonWebKey webKey, class System.Collections.Generic.ICollection`1&lt;string&gt;&amp; specifiedProps) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.WebKey.JsonWebKeyVerifier.IsAnyPrivateKeyParamSpecified(Microsoft.Azure.KeyVault.WebKey.JsonWebKey,System.Collections.Generic.ICollection{System.String}@)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function IsAnyPrivateKeyParamSpecified (webKey As JsonWebKey, ByRef specifiedProps As ICollection(Of String)) As Boolean" />
      <MemberSignature Language="F#" Value="abstract member IsAnyPrivateKeyParamSpecified : Microsoft.Azure.KeyVault.WebKey.JsonWebKey *  -&gt; bool&#xA;override this.IsAnyPrivateKeyParamSpecified : Microsoft.Azure.KeyVault.WebKey.JsonWebKey *  -&gt; bool" Usage="jsonWebKeyVerifier.IsAnyPrivateKeyParamSpecified (webKey, specifiedProps)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault.WebKey</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="webKey" Type="Microsoft.Azure.KeyVault.WebKey.JsonWebKey" />
        <Parameter Name="specifiedProps" Type="System.Collections.Generic.ICollection&lt;System.String&gt;&amp;" RefType="ref" />
      </Parameters>
      <Docs>
        <param name="webKey">Die Instanz zu überprüfen.</param>
        <param name="specifiedProps">Ein Verweis auf eine Variable, die die Liste der angegebenen Eigenschaften informiert. Aufrufer müssen die Variable festlegen, um <code>null</code> und überprüfen Sie den Wert nur, wenn diese Methode gibt <code>true</code>.</param>
        <summary>
            Bestimmt, ob das angegebene <see cref="T:Microsoft.Azure.KeyVault.WebKey.JsonWebKey" /> Instanz enthält, Werte in eine oder mehrere Eigenschaften, die den privaten Schlüssel darstellen. 
            </summary>
        <returns>
          <code>true</code>Wenn ein Wert in mindestens eine Eigenschaft, die beschreiben, den privaten Schlüssel gefunden wurde. <code>false</code> andernfalls.</returns>
        <remarks>To be added.</remarks>
        <para>Diese Methode wird verwendet, um private Schlüsselmaterial vor versehentlichen Datenlecks zu schützen.</para>
        <para>Wenn keine private Key-Eigenschaft (für den Typ des Schlüssels) in der Instanz angegeben wird, muss die Methode zurück.
            <code>false</code>und es keine Änderungen der <paramref name="specifiedProps" /> Parameter.</para>
        <para>Wenn eine oder mehrere private Schlüsseleigenschaft angegeben wird, muss die Methode zurückgeben <code>true</code> und optional festgelegte <paramref name="specifiedProps" /> mit einem Wert – in der Regel eine <see cref="T:System.Collections.Generic.List`1" /> -mit den angegebenen Eigenschaften.</para>
      </Docs>
    </Member>
    <Member MemberName="IsOperationCompatible">
      <MemberSignature Language="C#" Value="public bool IsOperationCompatible (string opName);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance bool IsOperationCompatible(string opName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.WebKey.JsonWebKeyVerifier.IsOperationCompatible(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function IsOperationCompatible (opName As String) As Boolean" />
      <MemberSignature Language="F#" Value="member this.IsOperationCompatible : string -&gt; bool" Usage="jsonWebKeyVerifier.IsOperationCompatible opName" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault.WebKey</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="opName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="opName">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IsOperationValid">
      <MemberSignature Language="C#" Value="public static bool IsOperationValid (string opName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig bool IsOperationValid(string opName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.WebKey.JsonWebKeyVerifier.IsOperationValid(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function IsOperationValid (opName As String) As Boolean" />
      <MemberSignature Language="F#" Value="static member IsOperationValid : string -&gt; bool" Usage="Microsoft.Azure.KeyVault.WebKey.JsonWebKeyVerifier.IsOperationValid opName" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault.WebKey</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="opName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="opName">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IsPrivateKeyComplete">
      <MemberSignature Language="C#" Value="public virtual bool IsPrivateKeyComplete (Microsoft.Azure.KeyVault.WebKey.JsonWebKey webKey, ref System.Collections.Generic.ICollection&lt;string&gt; missingProps);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance bool IsPrivateKeyComplete(class Microsoft.Azure.KeyVault.WebKey.JsonWebKey webKey, class System.Collections.Generic.ICollection`1&lt;string&gt;&amp; missingProps) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.WebKey.JsonWebKeyVerifier.IsPrivateKeyComplete(Microsoft.Azure.KeyVault.WebKey.JsonWebKey,System.Collections.Generic.ICollection{System.String}@)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function IsPrivateKeyComplete (webKey As JsonWebKey, ByRef missingProps As ICollection(Of String)) As Boolean" />
      <MemberSignature Language="F#" Value="abstract member IsPrivateKeyComplete : Microsoft.Azure.KeyVault.WebKey.JsonWebKey *  -&gt; bool&#xA;override this.IsPrivateKeyComplete : Microsoft.Azure.KeyVault.WebKey.JsonWebKey *  -&gt; bool" Usage="jsonWebKeyVerifier.IsPrivateKeyComplete (webKey, missingProps)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault.WebKey</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="webKey" Type="Microsoft.Azure.KeyVault.WebKey.JsonWebKey" />
        <Parameter Name="missingProps" Type="System.Collections.Generic.ICollection&lt;System.String&gt;&amp;" RefType="ref" />
      </Parameters>
      <Docs>
        <param name="webKey">To be added.</param>
        <param name="missingProps">To be added.</param>
        <summary>
            Identisch mit <see cref="M:Microsoft.Azure.KeyVault.WebKey.JsonWebKeyVerifier.IsPublicKeyComplete(Microsoft.Azure.KeyVault.WebKey.JsonWebKey,System.Collections.Generic.ICollection{System.String}@)" />, aber für den privaten Schlüssel.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IsPrivateKeyValid">
      <MemberSignature Language="C#" Value="public virtual bool IsPrivateKeyValid (Microsoft.Azure.KeyVault.WebKey.JsonWebKey webKey, ref string errorMsg);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance bool IsPrivateKeyValid(class Microsoft.Azure.KeyVault.WebKey.JsonWebKey webKey, string&amp; errorMsg) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.WebKey.JsonWebKeyVerifier.IsPrivateKeyValid(Microsoft.Azure.KeyVault.WebKey.JsonWebKey,System.String@)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function IsPrivateKeyValid (webKey As JsonWebKey, ByRef errorMsg As String) As Boolean" />
      <MemberSignature Language="F#" Value="abstract member IsPrivateKeyValid : Microsoft.Azure.KeyVault.WebKey.JsonWebKey *  -&gt; bool&#xA;override this.IsPrivateKeyValid : Microsoft.Azure.KeyVault.WebKey.JsonWebKey *  -&gt; bool" Usage="jsonWebKeyVerifier.IsPrivateKeyValid (webKey, errorMsg)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault.WebKey</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="webKey" Type="Microsoft.Azure.KeyVault.WebKey.JsonWebKey" />
        <Parameter Name="errorMsg" Type="System.String&amp;" RefType="ref" />
      </Parameters>
      <Docs>
        <param name="webKey">To be added.</param>
        <param name="errorMsg">To be added.</param>
        <summary>
            Identisch mit <see cref="M:Microsoft.Azure.KeyVault.WebKey.JsonWebKeyVerifier.IsPublicKeyValid(Microsoft.Azure.KeyVault.WebKey.JsonWebKey,System.String@)" />, aber für den privaten Schlüssel.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IsPropertyUsed">
      <MemberSignature Language="C#" Value="public bool IsPropertyUsed (string propName);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance bool IsPropertyUsed(string propName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.WebKey.JsonWebKeyVerifier.IsPropertyUsed(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function IsPropertyUsed (propName As String) As Boolean" />
      <MemberSignature Language="F#" Value="member this.IsPropertyUsed : string -&gt; bool" Usage="jsonWebKeyVerifier.IsPropertyUsed propName" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault.WebKey</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="propName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="propName">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IsPublicKeyComplete">
      <MemberSignature Language="C#" Value="public virtual bool IsPublicKeyComplete (Microsoft.Azure.KeyVault.WebKey.JsonWebKey webKey, ref System.Collections.Generic.ICollection&lt;string&gt; missingProps);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance bool IsPublicKeyComplete(class Microsoft.Azure.KeyVault.WebKey.JsonWebKey webKey, class System.Collections.Generic.ICollection`1&lt;string&gt;&amp; missingProps) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.WebKey.JsonWebKeyVerifier.IsPublicKeyComplete(Microsoft.Azure.KeyVault.WebKey.JsonWebKey,System.Collections.Generic.ICollection{System.String}@)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function IsPublicKeyComplete (webKey As JsonWebKey, ByRef missingProps As ICollection(Of String)) As Boolean" />
      <MemberSignature Language="F#" Value="abstract member IsPublicKeyComplete : Microsoft.Azure.KeyVault.WebKey.JsonWebKey *  -&gt; bool&#xA;override this.IsPublicKeyComplete : Microsoft.Azure.KeyVault.WebKey.JsonWebKey *  -&gt; bool" Usage="jsonWebKeyVerifier.IsPublicKeyComplete (webKey, missingProps)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault.WebKey</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="webKey" Type="Microsoft.Azure.KeyVault.WebKey.JsonWebKey" />
        <Parameter Name="missingProps" Type="System.Collections.Generic.ICollection&lt;System.String&gt;&amp;" RefType="ref" />
      </Parameters>
      <Docs>
        <param name="webKey">Die Instanz zu überprüfen.</param>
        <param name="missingProps">Ein Verweis auf eine Variable, die die Liste der fehlenden Eigenschaften informiert. Aufrufer müssen die Variable festlegen, um <code>null</code>, und überprüfen Sie den Wert nur, wenn diese Methode gibt <code>false</code>.</param>
        <summary>
            Bestimmt, ob das angegebene <see cref="T:Microsoft.Azure.KeyVault.WebKey.JsonWebKey" /> Instanz enthält Werte, die Eigenschaften, die den öffentlichen Schlüssel darstellen. 
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <para>Wenn alle erforderliche public Key Eigenschaften (für den Typ des Schlüssels) in der Instanz angegeben sind, muss die Methode zurück.
            <code>true</code>und es keine Änderungen der <paramref name="missingProps" /> Parameter.</para>
        <para>Wenn einige public Key-Eigenschaft nicht vorhanden ist, muss die Methode zurückgeben <code>false</code> und legen Sie <paramref name="missingProps" /> mit einem Wert – in der Regel eine <see cref="T:System.Collections.Generic.List`1" /> -alle fehlenden Eigenschaften enthält.</para>
      </Docs>
    </Member>
    <Member MemberName="IsPublicKeyCrypto">
      <MemberSignature Language="C#" Value="public abstract bool IsPublicKeyCrypto { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool IsPublicKeyCrypto" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.KeyVault.WebKey.JsonWebKeyVerifier.IsPublicKeyCrypto" />
      <MemberSignature Language="VB.NET" Value="Public MustOverride ReadOnly Property IsPublicKeyCrypto As Boolean" />
      <MemberSignature Language="F#" Value="member this.IsPublicKeyCrypto : bool" Usage="Microsoft.Azure.KeyVault.WebKey.JsonWebKeyVerifier.IsPublicKeyCrypto" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault.WebKey</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Gibt an, ob der Typ des Schlüssels, der von diesem Objekt überprüft Algorithmen für öffentliche Schlüssel unterstützt.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
        <code>true</code>
        <see cref="M:Microsoft.Azure.KeyVault.WebKey.JsonWebKeyVerifier.IsPublicKeyComplete(Microsoft.Azure.KeyVault.WebKey.JsonWebKey,System.Collections.Generic.ICollection{System.String}@)" />
        <see cref="M:Microsoft.Azure.KeyVault.WebKey.JsonWebKeyVerifier.IsPublicKeyValid(Microsoft.Azure.KeyVault.WebKey.JsonWebKey,System.String@)" />
        <see cref="M:Microsoft.Azure.KeyVault.WebKey.JsonWebKeyVerifier.IsPrivateKeyComplete(Microsoft.Azure.KeyVault.WebKey.JsonWebKey,System.Collections.Generic.ICollection{System.String}@)" />
        <see cref="M:Microsoft.Azure.KeyVault.WebKey.JsonWebKeyVerifier.IsPrivateKeyValid(Microsoft.Azure.KeyVault.WebKey.JsonWebKey,System.String@)" />
      </Docs>
    </Member>
    <Member MemberName="IsPublicKeyValid">
      <MemberSignature Language="C#" Value="public virtual bool IsPublicKeyValid (Microsoft.Azure.KeyVault.WebKey.JsonWebKey webKey, ref string errorMsg);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance bool IsPublicKeyValid(class Microsoft.Azure.KeyVault.WebKey.JsonWebKey webKey, string&amp; errorMsg) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.WebKey.JsonWebKeyVerifier.IsPublicKeyValid(Microsoft.Azure.KeyVault.WebKey.JsonWebKey,System.String@)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function IsPublicKeyValid (webKey As JsonWebKey, ByRef errorMsg As String) As Boolean" />
      <MemberSignature Language="F#" Value="abstract member IsPublicKeyValid : Microsoft.Azure.KeyVault.WebKey.JsonWebKey *  -&gt; bool&#xA;override this.IsPublicKeyValid : Microsoft.Azure.KeyVault.WebKey.JsonWebKey *  -&gt; bool" Usage="jsonWebKeyVerifier.IsPublicKeyValid (webKey, errorMsg)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault.WebKey</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="webKey" Type="Microsoft.Azure.KeyVault.WebKey.JsonWebKey" />
        <Parameter Name="errorMsg" Type="System.String&amp;" RefType="ref" />
      </Parameters>
      <Docs>
        <param name="webKey">Die Instanz zu überprüfen.</param>
        <param name="errorMsg">Ein Verweis auf eine Variable, die eine Fehlermeldung enthält. Aufrufer müssen die Variable festlegen, um <code>null</code>, und überprüfen Sie den Wert nur, wenn diese Methode gibt <code>false</code>.</param>
        <summary>
            Bestimmt, ob das angegebene <see cref="T:Microsoft.Azure.KeyVault.WebKey.JsonWebKey" /> Instanz einen möglicherweise gültigen öffentlichen Schlüssel enthält (siehe "Hinweise"). 
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <para>Da einen Schlüssel vollständig überprüft werden Unfeasable Anteil der Speicherressourcen erfordern möglicherweise, hat diese Methode nur für offensichtlich Probleme zu überprüfen. Als Richtlinie sagen wir, dass der Code nur offensichtlich Probleme überprüft, ob sie in konstanter Zeit ausgeführt wird.
            Ist es perfekt geeignet für in einer Implementierung, geschieht nichts und einfach return <code>true</code>.</para>
        <para>Diese Methode setzt voraus, dass <see cref="M:Microsoft.Azure.KeyVault.WebKey.JsonWebKeyVerifier.IsPublicKeyComplete(Microsoft.Azure.KeyVault.WebKey.JsonWebKey,System.Collections.Generic.ICollection{System.String}@)" /> aufgerufen und zurückgegeben wurde <code>true</code>. Es ist nicht auf das Vorhandensein des erforderlichen Eigenschaften erneut testen. Es auslösen <see cref="T:System.NullReferenceException" /> , wenn der Aufrufer finden Sie unter nicht <see cref="M:Microsoft.Azure.KeyVault.WebKey.JsonWebKeyVerifier.IsPublicKeyComplete(Microsoft.Azure.KeyVault.WebKey.JsonWebKey,System.Collections.Generic.ICollection{System.String}@)" /> zurückgeben <code>true</code> erste.</para>
        <para>Findet der Valiation Code kein Problem, muss diese Methode zurückgeben <code>true</code> ohne Ändern des Werts eines <paramref name="errorMsg" />.</para>
        <para>Wenn ein Problem gefunden wird, muss diese Methode zurückgeben <code>false</code> , und teilen Sie die Informationen in den <paramref name="errorMsg" /> Parameter.</para>
      </Docs>
    </Member>
    <Member MemberName="IsSecretKeyComplete">
      <MemberSignature Language="C#" Value="public virtual bool IsSecretKeyComplete (Microsoft.Azure.KeyVault.WebKey.JsonWebKey webKey, ref System.Collections.Generic.ICollection&lt;string&gt; missingProps);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance bool IsSecretKeyComplete(class Microsoft.Azure.KeyVault.WebKey.JsonWebKey webKey, class System.Collections.Generic.ICollection`1&lt;string&gt;&amp; missingProps) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.WebKey.JsonWebKeyVerifier.IsSecretKeyComplete(Microsoft.Azure.KeyVault.WebKey.JsonWebKey,System.Collections.Generic.ICollection{System.String}@)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function IsSecretKeyComplete (webKey As JsonWebKey, ByRef missingProps As ICollection(Of String)) As Boolean" />
      <MemberSignature Language="F#" Value="abstract member IsSecretKeyComplete : Microsoft.Azure.KeyVault.WebKey.JsonWebKey *  -&gt; bool&#xA;override this.IsSecretKeyComplete : Microsoft.Azure.KeyVault.WebKey.JsonWebKey *  -&gt; bool" Usage="jsonWebKeyVerifier.IsSecretKeyComplete (webKey, missingProps)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault.WebKey</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="webKey" Type="Microsoft.Azure.KeyVault.WebKey.JsonWebKey" />
        <Parameter Name="missingProps" Type="System.Collections.Generic.ICollection&lt;System.String&gt;&amp;" RefType="ref" />
      </Parameters>
      <Docs>
        <param name="webKey">Die Instanz zu überprüfen.</param>
        <param name="missingProps">Ein Verweis auf eine Variable, die die Liste der fehlenden Eigenschaften informiert. Aufrufer müssen die Variable festlegen, um <code>null</code>, und überprüfen Sie den Wert nur, wenn diese Methode gibt <code>false</code>.</param>
        <summary>
            Bestimmt, ob das angegebene <see cref="T:Microsoft.Azure.KeyVault.WebKey.JsonWebKey" /> Instanz enthält Werte, die Eigenschaften, die für den geheimen Schlüssel darstellen. 
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <para>Wenn alle erforderliche für den geheimen Schlüssel Eigenschaften (für den Typ des Schlüssels) in der Instanz angegeben sind, muss die Methode zurück.
            <code>true</code>und es keine Änderungen der <paramref name="missingProps" /> Parameter.</para>
        <para>Wenn eine bestimmte Eigenschaft nicht vorhanden ist, muss die Methode zurückgeben <code>false</code> und legen Sie <paramref name="missingProps" /> in einen Wert – in der Regel eine <see cref="T:System.Collections.Generic.List`1" /> -alle fehlenden Eigenschaften enthält.</para>
      </Docs>
    </Member>
    <Member MemberName="IsSecretKeyValid">
      <MemberSignature Language="C#" Value="public virtual bool IsSecretKeyValid (Microsoft.Azure.KeyVault.WebKey.JsonWebKey webKey, ref string errorMsg);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance bool IsSecretKeyValid(class Microsoft.Azure.KeyVault.WebKey.JsonWebKey webKey, string&amp; errorMsg) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.WebKey.JsonWebKeyVerifier.IsSecretKeyValid(Microsoft.Azure.KeyVault.WebKey.JsonWebKey,System.String@)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function IsSecretKeyValid (webKey As JsonWebKey, ByRef errorMsg As String) As Boolean" />
      <MemberSignature Language="F#" Value="abstract member IsSecretKeyValid : Microsoft.Azure.KeyVault.WebKey.JsonWebKey *  -&gt; bool&#xA;override this.IsSecretKeyValid : Microsoft.Azure.KeyVault.WebKey.JsonWebKey *  -&gt; bool" Usage="jsonWebKeyVerifier.IsSecretKeyValid (webKey, errorMsg)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault.WebKey</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="webKey" Type="Microsoft.Azure.KeyVault.WebKey.JsonWebKey" />
        <Parameter Name="errorMsg" Type="System.String&amp;" RefType="ref" />
      </Parameters>
      <Docs>
        <param name="webKey">Die Instanz zu überprüfen.</param>
        <param name="errorMsg">Ein Verweis auf eine Variable, die eine Fehlermeldung enthält. Aufrufer müssen die Variable festlegen, um <code>null</code>, und überprüfen Sie den Wert nur, wenn diese Methode gibt <code>false</code>.</param>
        <summary>
            Bestimmt, ob das angegebene <see cref="T:Microsoft.Azure.KeyVault.WebKey.JsonWebKey" /> Instanz enthält möglicherweise gültigen für den geheimen Schlüssel (siehe "Hinweise"). 
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <para>Da einen Schlüssel vollständig überprüft werden Unfeasable Anteil der Speicherressourcen erfordern möglicherweise, hat diese Methode nur für offensichtlich Probleme zu überprüfen. Als Richtlinie sagen wir, dass der Code nur offensichtlich Probleme überprüft, ob sie in konstanter Zeit ausgeführt wird.
            Ist es perfekt geeignet für in einer Implementierung, geschieht nichts und einfach return <code>true</code>.</para>
        <para>Diese Methode setzt voraus, dass <see cref="M:Microsoft.Azure.KeyVault.WebKey.JsonWebKeyVerifier.IsSecretKeyComplete(Microsoft.Azure.KeyVault.WebKey.JsonWebKey,System.Collections.Generic.ICollection{System.String}@)" /> aufgerufen und zurückgegeben wurde <code>true</code>. Es ist nicht auf das Vorhandensein des erforderlichen Eigenschaften erneut testen. Es auslösen <see cref="T:System.NullReferenceException" /> , wenn der Aufrufer finden Sie unter nicht <see cref="M:Microsoft.Azure.KeyVault.WebKey.JsonWebKeyVerifier.IsSecretKeyComplete(Microsoft.Azure.KeyVault.WebKey.JsonWebKey,System.Collections.Generic.ICollection{System.String}@)" /> zurückgeben <code>true</code> erste.</para>
        <para>Findet der Valiation Code kein Problem, muss diese Methode zurückgeben <code>true</code> ohne Ändern des Werts eines <paramref name="errorMsg" />.</para>
        <para>Wenn ein Problem gefunden wird, muss diese Methode zurückgeben <code>false</code> , und teilen Sie die Informationen in den <paramref name="errorMsg" /> Parameter.</para>
      </Docs>
    </Member>
    <Member MemberName="IsSymmetricKeyComplete">
      <MemberSignature Language="C#" Value="public virtual bool IsSymmetricKeyComplete (Microsoft.Azure.KeyVault.WebKey.JsonWebKey webKey, ref System.Collections.Generic.ICollection&lt;string&gt; missingProps);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance bool IsSymmetricKeyComplete(class Microsoft.Azure.KeyVault.WebKey.JsonWebKey webKey, class System.Collections.Generic.ICollection`1&lt;string&gt;&amp; missingProps) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.WebKey.JsonWebKeyVerifier.IsSymmetricKeyComplete(Microsoft.Azure.KeyVault.WebKey.JsonWebKey,System.Collections.Generic.ICollection{System.String}@)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function IsSymmetricKeyComplete (webKey As JsonWebKey, ByRef missingProps As ICollection(Of String)) As Boolean" />
      <MemberSignature Language="F#" Value="abstract member IsSymmetricKeyComplete : Microsoft.Azure.KeyVault.WebKey.JsonWebKey *  -&gt; bool&#xA;override this.IsSymmetricKeyComplete : Microsoft.Azure.KeyVault.WebKey.JsonWebKey *  -&gt; bool" Usage="jsonWebKeyVerifier.IsSymmetricKeyComplete (webKey, missingProps)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault.WebKey</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="webKey" Type="Microsoft.Azure.KeyVault.WebKey.JsonWebKey" />
        <Parameter Name="missingProps" Type="System.Collections.Generic.ICollection&lt;System.String&gt;&amp;" RefType="ref" />
      </Parameters>
      <Docs>
        <param name="webKey">Die Instanz zu überprüfen.</param>
        <param name="missingProps">Ein Verweis auf eine Variable, die die Liste der fehlenden Eigenschaften informiert. Aufrufer müssen die Variable festlegen, um <code>null</code>, und überprüfen Sie den Wert nur, wenn diese Methode gibt <code>false</code>.</param>
        <summary>
            Bestimmt, ob das angegebene <see cref="T:Microsoft.Azure.KeyVault.WebKey.JsonWebKey" /> Instanz enthält Werte, die auf Eigenschaften, die den symmetrischen Schlüssel darstellen. 
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <para>Wenn alle erforderliche symmetrischen Schlüssel Eigenschaften (für den Typ des Schlüssels) in der Instanz angegeben sind, muss die Methode zurück.
            <code>true</code>und es keine Änderungen der <paramref name="missingProps" /> Parameter.</para>
        <para>Wenn eine bestimmte Eigenschaft nicht vorhanden ist, muss die Methode zurückgeben <code>false</code> und legen Sie <paramref name="missingProps" /> in einen Wert – in der Regel eine <see cref="T:System.Collections.Generic.List`1" /> -alle fehlenden Eigenschaften enthält.</para>
      </Docs>
    </Member>
    <Member MemberName="IsSymmetricKeyCrypto">
      <MemberSignature Language="C#" Value="public abstract bool IsSymmetricKeyCrypto { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool IsSymmetricKeyCrypto" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.KeyVault.WebKey.JsonWebKeyVerifier.IsSymmetricKeyCrypto" />
      <MemberSignature Language="VB.NET" Value="Public MustOverride ReadOnly Property IsSymmetricKeyCrypto As Boolean" />
      <MemberSignature Language="F#" Value="member this.IsSymmetricKeyCrypto : bool" Usage="Microsoft.Azure.KeyVault.WebKey.JsonWebKeyVerifier.IsSymmetricKeyCrypto" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault.WebKey</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Gibt an, ob der Typ des Schlüssels, der von diesem Objekt überprüft Algorithmen mit symmetrische Schlüssel unterstützt.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
        <code>true</code>
        <see cref="M:Microsoft.Azure.KeyVault.WebKey.JsonWebKeyVerifier.IsSymmetricKeyComplete(Microsoft.Azure.KeyVault.WebKey.JsonWebKey,System.Collections.Generic.ICollection{System.String}@)" />
        <see cref="M:Microsoft.Azure.KeyVault.WebKey.JsonWebKeyVerifier.IsSymmetricKeyValid(Microsoft.Azure.KeyVault.WebKey.JsonWebKey,System.String@)" />
      </Docs>
    </Member>
    <Member MemberName="IsSymmetricKeyValid">
      <MemberSignature Language="C#" Value="public virtual bool IsSymmetricKeyValid (Microsoft.Azure.KeyVault.WebKey.JsonWebKey webKey, ref string errorMsg);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance bool IsSymmetricKeyValid(class Microsoft.Azure.KeyVault.WebKey.JsonWebKey webKey, string&amp; errorMsg) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.WebKey.JsonWebKeyVerifier.IsSymmetricKeyValid(Microsoft.Azure.KeyVault.WebKey.JsonWebKey,System.String@)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function IsSymmetricKeyValid (webKey As JsonWebKey, ByRef errorMsg As String) As Boolean" />
      <MemberSignature Language="F#" Value="abstract member IsSymmetricKeyValid : Microsoft.Azure.KeyVault.WebKey.JsonWebKey *  -&gt; bool&#xA;override this.IsSymmetricKeyValid : Microsoft.Azure.KeyVault.WebKey.JsonWebKey *  -&gt; bool" Usage="jsonWebKeyVerifier.IsSymmetricKeyValid (webKey, errorMsg)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault.WebKey</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="webKey" Type="Microsoft.Azure.KeyVault.WebKey.JsonWebKey" />
        <Parameter Name="errorMsg" Type="System.String&amp;" RefType="ref" />
      </Parameters>
      <Docs>
        <param name="webKey">Die Instanz zu überprüfen.</param>
        <param name="errorMsg">Ein Verweis auf eine Variable, die eine Fehlermeldung enthält. Aufrufer müssen die Variable festlegen, um <code>null</code>, und überprüfen Sie den Wert nur, wenn diese Methode gibt <code>false</code>.</param>
        <summary>
            Bestimmt, ob das angegebene <see cref="T:Microsoft.Azure.KeyVault.WebKey.JsonWebKey" /> Instanz einen möglicherweise gültigen symmetrischen Schlüssel enthält (siehe "Hinweise"). 
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <para>Da einen Schlüssel vollständig überprüft werden Unfeasable Anteil der Speicherressourcen erfordern möglicherweise, hat diese Methode nur für offensichtlich Probleme zu überprüfen. Als Richtlinie sagen wir, dass der Code nur offensichtlich Probleme überprüft, ob sie in konstanter Zeit ausgeführt wird.
            Ist es perfekt geeignet für in einer Implementierung, geschieht nichts und einfach return <code>true</code>.</para>
        <para>Diese Methode setzt voraus, dass <see cref="M:Microsoft.Azure.KeyVault.WebKey.JsonWebKeyVerifier.IsSymmetricKeyComplete(Microsoft.Azure.KeyVault.WebKey.JsonWebKey,System.Collections.Generic.ICollection{System.String}@)" /> aufgerufen und zurückgegeben wurde <code>true</code>. Es ist nicht auf das Vorhandensein des erforderlichen Eigenschaften erneut testen. Es auslösen <see cref="T:System.NullReferenceException" /> , wenn der Aufrufer finden Sie unter nicht <see cref="M:Microsoft.Azure.KeyVault.WebKey.JsonWebKeyVerifier.IsSymmetricKeyComplete(Microsoft.Azure.KeyVault.WebKey.JsonWebKey,System.Collections.Generic.ICollection{System.String}@)" /> zurückgeben <code>true</code> erste.</para>
        <para>Findet der Valiation Code kein Problem, muss diese Methode zurückgeben <code>true</code> ohne Ändern des Werts eines <paramref name="errorMsg" />.</para>
        <para>Wenn ein Problem gefunden wird, muss diese Methode zurückgeben <code>false</code> , und teilen Sie die Informationen in den <paramref name="errorMsg" /> Parameter.</para>
      </Docs>
    </Member>
    <Member MemberName="Kty">
      <MemberSignature Language="C#" Value="public string Kty { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Kty" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.KeyVault.WebKey.JsonWebKeyVerifier.Kty" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Kty As String" />
      <MemberSignature Language="F#" Value="member this.Kty : string" Usage="Microsoft.Azure.KeyVault.WebKey.JsonWebKeyVerifier.Kty" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault.WebKey</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Gibt an, welche Art von Schlüssel für diese Prüfung gilt.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
        <see cref="T:Microsoft.Azure.KeyVault.WebKey.JsonWebKeyType" />
        <see cref="M:Microsoft.Azure.KeyVault.WebKey.JsonWebKeyVerifier.Register(Microsoft.Azure.KeyVault.WebKey.JsonWebKeyVerifier)" />
      </Docs>
    </Member>
    <Member MemberName="Register">
      <MemberSignature Language="C#" Value="public static void Register (Microsoft.Azure.KeyVault.WebKey.JsonWebKeyVerifier verifier);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void Register(class Microsoft.Azure.KeyVault.WebKey.JsonWebKeyVerifier verifier) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.WebKey.JsonWebKeyVerifier.Register(Microsoft.Azure.KeyVault.WebKey.JsonWebKeyVerifier)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Sub Register (verifier As JsonWebKeyVerifier)" />
      <MemberSignature Language="F#" Value="static member Register : Microsoft.Azure.KeyVault.WebKey.JsonWebKeyVerifier -&gt; unit" Usage="Microsoft.Azure.KeyVault.WebKey.JsonWebKeyVerifier.Register verifier" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault.WebKey</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="verifier" Type="Microsoft.Azure.KeyVault.WebKey.JsonWebKeyVerifier" />
      </Parameters>
      <Docs>
        <param name="verifier">Die Überprüfung zu registrieren.</param>
        <summary>
            Registriert eine Prüfung für einen <see cref="P:Microsoft.Azure.KeyVault.WebKey.JsonWebKeyVerifier.Kty" /> Wert.
            </summary>
        <remarks>To be added.</remarks>
        <see cref="P:Microsoft.Azure.KeyVault.WebKey.JsonWebKeyVerifier.Kty" />
        <see cref="T:Microsoft.Azure.KeyVault.WebKey.JsonWebKeyType" />
        <altmember cref="M:Microsoft.Azure.KeyVault.WebKey.JsonWebKeyVerifier.GetVerifier(System.String)" />
      </Docs>
    </Member>
    <Member MemberName="SurroundWithQuotes">
      <MemberSignature Language="C#" Value="protected static string SurroundWithQuotes (System.Collections.Generic.ICollection&lt;string&gt; items);" />
      <MemberSignature Language="ILAsm" Value=".method familystatic hidebysig string SurroundWithQuotes(class System.Collections.Generic.ICollection`1&lt;string&gt; items) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.WebKey.JsonWebKeyVerifier.SurroundWithQuotes(System.Collections.Generic.ICollection{System.String})" />
      <MemberSignature Language="VB.NET" Value="Protected Shared Function SurroundWithQuotes (items As ICollection(Of String)) As String" />
      <MemberSignature Language="F#" Value="static member SurroundWithQuotes : System.Collections.Generic.ICollection&lt;string&gt; -&gt; string" Usage="Microsoft.Azure.KeyVault.WebKey.JsonWebKeyVerifier.SurroundWithQuotes items" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault.WebKey</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="items" Type="System.Collections.Generic.ICollection&lt;System.String&gt;" />
      </Parameters>
      <Docs>
        <param name="items">To be added.</param>
        <summary>
            Hilfsmethode, die Zeichenfolgenwerte mit doppelten Anführungszeichen umgeben. 
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <code>"Foo", "Balken"</code>
      </Docs>
    </Member>
    <Member MemberName="ValidateKeyParameterSize">
      <MemberSignature Language="C#" Value="protected static bool ValidateKeyParameterSize (byte[] value, string name, int requiredSize, ref string errorMsg);" />
      <MemberSignature Language="ILAsm" Value=".method familystatic hidebysig bool ValidateKeyParameterSize(unsigned int8[] value, string name, int32 requiredSize, string&amp; errorMsg) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.WebKey.JsonWebKeyVerifier.ValidateKeyParameterSize(System.Byte[],System.String,System.Int32,System.String@)" />
      <MemberSignature Language="VB.NET" Value="Protected Shared Function ValidateKeyParameterSize (value As Byte(), name As String, requiredSize As Integer, ByRef errorMsg As String) As Boolean" />
      <MemberSignature Language="F#" Value="static member ValidateKeyParameterSize : byte[] * string * int *  -&gt; bool" Usage="Microsoft.Azure.KeyVault.WebKey.JsonWebKeyVerifier.ValidateKeyParameterSize (value, name, requiredSize, errorMsg)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault.WebKey</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="value" Type="System.Byte[]" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="requiredSize" Type="System.Int32" />
        <Parameter Name="errorMsg" Type="System.String&amp;" RefType="ref" />
      </Parameters>
      <Docs>
        <param name="value">Das Array, um zu überprüfen.</param>
        <param name="name">Der Arrayname, der verwendet werden kann, um Fehlermeldungen zu erstellen.</param>
        <param name="requiredSize">Die erforderliche Größe in Bytes.</param>
        <param name="errorMsg">Ein Verweis auf eine Variable, die die Fehlermeldung enthält. Dies wird nur festgelegt, wenn die-Methode zurückgibt <code>false</code>.</param>
        <summary>
            Hilfsmethode, die die Größe eines Bytearrays überprüft.
            </summary>
        <returns>
          <code>true</code>Wenn das Array eine gültige Größe hat; <code>false otherwise</code>.</returns>
        <remarks>To be added.</remarks>
        <para>Ein gültiges Array erfüllt folgende Kriterien:</para>
        <list type="bullet">
          <item>
            <description>ist kein <code>null</code>;</description>
          </item>
          <item>
            <description>die Länge beträgt mindestens <paramref name="requiredSize" />; und</description>
          </item>
          <item>
            <description>übermäßige führende Bytes werden Nullen.</description>
          </item>
        </list>
      </Docs>
    </Member>
    <Member MemberName="Verify">
      <MemberSignature Language="C#" Value="public bool Verify (Microsoft.Azure.KeyVault.WebKey.JsonWebKey webKey, Microsoft.Azure.KeyVault.WebKey.JsonWebKeyVerifier.Options options, ref string error);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance bool Verify(class Microsoft.Azure.KeyVault.WebKey.JsonWebKey webKey, valuetype Microsoft.Azure.KeyVault.WebKey.JsonWebKeyVerifier/Options options, string&amp; error) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.WebKey.JsonWebKeyVerifier.Verify(Microsoft.Azure.KeyVault.WebKey.JsonWebKey,Microsoft.Azure.KeyVault.WebKey.JsonWebKeyVerifier.Options,System.String@)" />
      <MemberSignature Language="F#" Value="member this.Verify : Microsoft.Azure.KeyVault.WebKey.JsonWebKey * Microsoft.Azure.KeyVault.WebKey.JsonWebKeyVerifier.Options *  -&gt; bool" Usage="jsonWebKeyVerifier.Verify (webKey, options, error)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault.WebKey</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="webKey" Type="Microsoft.Azure.KeyVault.WebKey.JsonWebKey" />
        <Parameter Name="options" Type="Microsoft.Azure.KeyVault.WebKey.JsonWebKeyVerifier+Options" />
        <Parameter Name="error" Type="System.String&amp;" RefType="ref" />
      </Parameters>
      <Docs>
        <param name="webKey">Die Instanz zu überprüfen.</param>
        <param name="options">Gibt an, wie ist eine Überprüfung der verhält.</param>
        <param name="error">Ein Verweis auf eine Variable, die die Fehlermeldung mitteilt, wenn die Überprüfung fehlschlägt. Dies wird nur festgelegt, wenn die-Methode zurückgibt <code>false</code>. Wenn die-Methode zurückgibt <code>true</code> oder eine Ausnahme auslöst, die <paramref name="error" /> nicht anzeigen, die geändert wird.</param>
        <summary>
            Überprüft die angegebene JsonWebKey-Instanz an. 
            </summary>
        <returns>
          <code>true</code>Wenn der Wert JsonWebKey gültig ist <code>false otherwise</code>.</returns>
        <remarks>To be added.</remarks>
        <para>Zuerst daraufhin überprüft die <see cref="P:Microsoft.Azure.KeyVault.WebKey.JsonWebKey.Kty" /> Eigenschaft, um eine Instanz Verifier auszuwählen (Weitere Informationen finden Sie unter der <see cref="M:Microsoft.Azure.KeyVault.WebKey.JsonWebKeyVerifier.Register(Microsoft.Azure.KeyVault.WebKey.JsonWebKeyVerifier)" /> Methode). Wenn eine Prüfung gefunden wird, wird er verwendet zum Überprüfen, ob der Schlüssel mit dem entsprechenden Schlüsseltyp entspricht.</para>
        <exception cref="T:System.ArgumentNullException">Wenn die <paramref name="webKey" /> -Parameter ist null.</exception>
        <exception cref="T:System.ArgumentException">Wenn die <paramref name="options" /> Parameter enthält ungültige Optionen.</exception>
        <exception cref="T:Microsoft.Azure.KeyVault.WebKey.JsonWebKeyVerificationException">Das Objekt JsonWebKey ist "Invalid" und "die Option <see cref="F:Microsoft.Azure.KeyVault.WebKey.JsonWebKeyVerifier.Options.ThrowException" /> angegeben wurde.</exception>
        <altmember cref="T:Microsoft.Azure.KeyVault.WebKey.JsonWebKeyVerifier.Options" />
      </Docs>
    </Member>
    <Member MemberName="VerifyByKeyType">
      <MemberSignature Language="C#" Value="public static bool VerifyByKeyType (Microsoft.Azure.KeyVault.WebKey.JsonWebKey webKey, Microsoft.Azure.KeyVault.WebKey.JsonWebKeyVerifier.Options options, ref string error);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig bool VerifyByKeyType(class Microsoft.Azure.KeyVault.WebKey.JsonWebKey webKey, valuetype Microsoft.Azure.KeyVault.WebKey.JsonWebKeyVerifier/Options options, string&amp; error) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.WebKey.JsonWebKeyVerifier.VerifyByKeyType(Microsoft.Azure.KeyVault.WebKey.JsonWebKey,Microsoft.Azure.KeyVault.WebKey.JsonWebKeyVerifier.Options,System.String@)" />
      <MemberSignature Language="F#" Value="static member VerifyByKeyType : Microsoft.Azure.KeyVault.WebKey.JsonWebKey * Microsoft.Azure.KeyVault.WebKey.JsonWebKeyVerifier.Options *  -&gt; bool" Usage="Microsoft.Azure.KeyVault.WebKey.JsonWebKeyVerifier.VerifyByKeyType (webKey, options, error)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault.WebKey</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="webKey" Type="Microsoft.Azure.KeyVault.WebKey.JsonWebKey" />
        <Parameter Name="options" Type="Microsoft.Azure.KeyVault.WebKey.JsonWebKeyVerifier+Options" />
        <Parameter Name="error" Type="System.String&amp;" RefType="ref" />
      </Parameters>
      <Docs>
        <param name="webKey"></param>
        <param name="options"></param>
        <param name="error"></param>
        <summary>
            Überprüft die angegebene JsonWebKey-Instanz gemäß <see cref="P:Microsoft.Azure.KeyVault.WebKey.JsonWebKey.Kty" />.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <see cref="P:Microsoft.Azure.KeyVault.WebKey.JsonWebKey.Kty" />
        <see cref="M:Microsoft.Azure.KeyVault.WebKey.JsonWebKeyVerifier.Verify(Microsoft.Azure.KeyVault.WebKey.JsonWebKey,Microsoft.Azure.KeyVault.WebKey.JsonWebKeyVerifier.Options,System.String@)" />
        <altmember cref="M:Microsoft.Azure.KeyVault.WebKey.JsonWebKeyVerifier.Verify(Microsoft.Azure.KeyVault.WebKey.JsonWebKey,Microsoft.Azure.KeyVault.WebKey.JsonWebKeyVerifier.Options,System.String@)" />
      </Docs>
    </Member>
  </Members>
</Type>