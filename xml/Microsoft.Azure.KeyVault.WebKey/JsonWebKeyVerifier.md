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
            <span data-ttu-id="9b855-101">Eine Klasse, die überprüft, Instanzen von ob <see cref="T:Microsoft.Azure.KeyVault.WebKey.JsonWebKey" /> gemäß Schlüsseltyp.</span><span class="sxs-lookup"><span data-stu-id="9b855-101">A class that verifies instances of <see cref="T:Microsoft.Azure.KeyVault.WebKey.JsonWebKey" /> according to key type.</span></span> 
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
        <param name="kty"><span data-ttu-id="9b855-102">Gibt an, welche Art von Schlüssel für diese Prüfung gilt.</span><span class="sxs-lookup"><span data-stu-id="9b855-102">Indicates which type of key this verifier applies to.</span></span></param>
        <summary>
            <span data-ttu-id="9b855-103">Initialisiert eine neue Instanz den angegebenen Wert festlegen, in der <see cref="P:Microsoft.Azure.KeyVault.WebKey.JsonWebKeyVerifier.Kty" /> Eigenschaft.</span><span class="sxs-lookup"><span data-stu-id="9b855-103">Initializes a new instance setting the specified value in the <see cref="P:Microsoft.Azure.KeyVault.WebKey.JsonWebKeyVerifier.Kty" /> property.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentNullException"><span data-ttu-id="9b855-104">Wenn der angegebene Wert ist <code>null</code>, leer oder ein Leerzeichen.</span><span class="sxs-lookup"><span data-stu-id="9b855-104">If the specified value is <code>null</code>, empty or whitespace.</span></span></exception>
        <exception cref="T:System.ArgumentException"><span data-ttu-id="9b855-105">Wenn der angegebene Wert ein ungültige Zeichen enthält.</span><span class="sxs-lookup"><span data-stu-id="9b855-105">If the specified value contains invalid characters.</span></span></exception>
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
            <span data-ttu-id="9b855-106">Fügt der angegebenen Auflistung alle Vorgänge, die mit Schlüsseln erfolgen können, die von diesem Objekt, dessen Typ behandelt wird.</span><span class="sxs-lookup"><span data-stu-id="9b855-106">Adds to the specified collection all operations that can be performed with keys whose type is handled by this object.</span></span>
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
            <span data-ttu-id="9b855-107">Hilfsmethode, die den Vorgang zum Erstellen einer Sammlung (falls erforderlich) verknüpft und ein Element hinzugefügt wird.</span><span class="sxs-lookup"><span data-stu-id="9b855-107">Helper method that joins the operation of creating a collection (if required) and adding an item to it.</span></span>
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
            <span data-ttu-id="9b855-108">Fügt der angegebenen Auflistung alle JsonWebKey-Eigenschaften, die Schlüssel sind von diesem Objekt, dessen Typ behandelt wird.</span><span class="sxs-lookup"><span data-stu-id="9b855-108">Adds to the specified collection all JsonWebKey properties that are useful to keys whose type is handled by this object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <para><span data-ttu-id="9b855-109">Diese Methode muss JSON-Eigenschaftennamen, hinzufügen, z. B. <code>"crv"</code>, <code>"p"</code>usw. C#-Eigenschaftennamen müssen nicht hinzugefügt.</span><span class="sxs-lookup"><span data-stu-id="9b855-109">This method must add JSON property names, such as <code>"crv"</code>, <code>"p"</code>, etc. It must not add C# property names.</span></span></para>
        <para><span data-ttu-id="9b855-110">Diese Methode keinen hinzuzufügende <code>"kid"</code>, <code>"kty"</code> und <code>"key_ops"</code>.</span><span class="sxs-lookup"><span data-stu-id="9b855-110">This method doesn't have to add <code>"kid"</code>, <code>"kty"</code> and <code>"key_ops"</code>.</span></span>
            <span data-ttu-id="9b855-111">Es wird angenommen, dass Thesaurus-Eigenschaften für alle Schlüssel hilfreich sein.</span><span class="sxs-lookup"><span data-stu-id="9b855-111">Thes properties are assumed to be useful to all keys.</span></span></para>
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
            <span data-ttu-id="9b855-112">Gibt die Überprüfung zurück, registriert wird, damit der angegebene Kty-Wert oder null, wenn der Wert für Kty nicht registriert wurde.</span><span class="sxs-lookup"><span data-stu-id="9b855-112">Returns the verifier registered for the specified kty value, or null if the kty value was not registered.</span></span>
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
            <span data-ttu-id="9b855-113">Gibt an, ob der Typ des Schlüssels, der von diesem Objekt überprüft eine geheime Komponente wie eine Hardware-Schlüsseltoken enthält.</span><span class="sxs-lookup"><span data-stu-id="9b855-113">Tells if the type of key verified by this object contains a secret component, such as a hardware key token.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
        <code><span data-ttu-id="9b855-114">true</span><span class="sxs-lookup"><span data-stu-id="9b855-114">true</span></span></code>
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
        <param name="webKey"><span data-ttu-id="9b855-115">Die Instanz zu überprüfen.</span><span class="sxs-lookup"><span data-stu-id="9b855-115">The instance to verify.</span></span></param>
        <param name="specifiedProps"><span data-ttu-id="9b855-116">Ein Verweis auf eine Variable, die die Liste der angegebenen Eigenschaften informiert.</span><span class="sxs-lookup"><span data-stu-id="9b855-116">A reference to a variable that tells the list of specified properties.</span></span> <span data-ttu-id="9b855-117">Aufrufer müssen die Variable festlegen, um <code>null</code> und überprüfen Sie den Wert nur, wenn diese Methode gibt <code>true</code>.</span><span class="sxs-lookup"><span data-stu-id="9b855-117">Callers must set the variable to <code>null</code> and examine the value only if this method returns <code>true</code>.</span></span></param>
        <summary>
            <span data-ttu-id="9b855-118">Bestimmt, ob das angegebene <see cref="T:Microsoft.Azure.KeyVault.WebKey.JsonWebKey" /> Instanz enthält, Werte in eine oder mehrere Eigenschaften, die den privaten Schlüssel darstellen.</span><span class="sxs-lookup"><span data-stu-id="9b855-118">Determines if the specified <see cref="T:Microsoft.Azure.KeyVault.WebKey.JsonWebKey" /> instance contains values in one or more properties that represent the private key.</span></span> 
            </summary>
        <returns>
          <span data-ttu-id="9b855-119"><code>true</code>Wenn ein Wert in mindestens eine Eigenschaft, die beschreiben, den privaten Schlüssel gefunden wurde. <code>false</code> andernfalls.</span><span class="sxs-lookup"><span data-stu-id="9b855-119"><code>true</code> if a value is found in at least one property that describe the private key; <code>false</code> otherwise.</span></span></returns>
        <remarks>To be added.</remarks>
        <para><span data-ttu-id="9b855-120">Diese Methode wird verwendet, um private Schlüsselmaterial vor versehentlichen Datenlecks zu schützen.</span><span class="sxs-lookup"><span data-stu-id="9b855-120">This method is used to protect private key material from accidental leakage.</span></span></para>
        <para><span data-ttu-id="9b855-121">Wenn keine private Key-Eigenschaft (für den Typ des Schlüssels) in der Instanz angegeben wird, muss die Methode zurück.</span><span class="sxs-lookup"><span data-stu-id="9b855-121">If no private key property (for the key type) is specified in the instance, the method must return</span></span>
            <span data-ttu-id="9b855-122"><code>false</code>und es keine Änderungen der <paramref name="specifiedProps" /> Parameter.</span><span class="sxs-lookup"><span data-stu-id="9b855-122"><code>false</code> and not modify the <paramref name="specifiedProps" /> parameter.</span></span></para>
        <para><span data-ttu-id="9b855-123">Wenn eine oder mehrere private Schlüsseleigenschaft angegeben wird, muss die Methode zurückgeben <code>true</code> und optional festgelegte <paramref name="specifiedProps" /> mit einem Wert – in der Regel eine <see cref="T:System.Collections.Generic.List`1" /> -mit den angegebenen Eigenschaften.</span><span class="sxs-lookup"><span data-stu-id="9b855-123">If one or more private key property is specified, the method must return <code>true</code> and optionally set <paramref name="specifiedProps" /> with a value - typically a <see cref="T:System.Collections.Generic.List`1" /> - containing the specified properties.</span></span></para>
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
            <span data-ttu-id="9b855-124">Identisch mit <see cref="M:Microsoft.Azure.KeyVault.WebKey.JsonWebKeyVerifier.IsPublicKeyComplete(Microsoft.Azure.KeyVault.WebKey.JsonWebKey,System.Collections.Generic.ICollection{System.String}@)" />, aber für den privaten Schlüssel.</span><span class="sxs-lookup"><span data-stu-id="9b855-124">Same as <see cref="M:Microsoft.Azure.KeyVault.WebKey.JsonWebKeyVerifier.IsPublicKeyComplete(Microsoft.Azure.KeyVault.WebKey.JsonWebKey,System.Collections.Generic.ICollection{System.String}@)" />, but for the private key.</span></span>
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
            <span data-ttu-id="9b855-125">Identisch mit <see cref="M:Microsoft.Azure.KeyVault.WebKey.JsonWebKeyVerifier.IsPublicKeyValid(Microsoft.Azure.KeyVault.WebKey.JsonWebKey,System.String@)" />, aber für den privaten Schlüssel.</span><span class="sxs-lookup"><span data-stu-id="9b855-125">Same as <see cref="M:Microsoft.Azure.KeyVault.WebKey.JsonWebKeyVerifier.IsPublicKeyValid(Microsoft.Azure.KeyVault.WebKey.JsonWebKey,System.String@)" />, but for the private key.</span></span>
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
        <param name="webKey"><span data-ttu-id="9b855-126">Die Instanz zu überprüfen.</span><span class="sxs-lookup"><span data-stu-id="9b855-126">The instance to verify.</span></span></param>
        <param name="missingProps"><span data-ttu-id="9b855-127">Ein Verweis auf eine Variable, die die Liste der fehlenden Eigenschaften informiert.</span><span class="sxs-lookup"><span data-stu-id="9b855-127">A reference to a variable that tells the list of missing properties.</span></span> <span data-ttu-id="9b855-128">Aufrufer müssen die Variable festlegen, um <code>null</code>, und überprüfen Sie den Wert nur, wenn diese Methode gibt <code>false</code>.</span><span class="sxs-lookup"><span data-stu-id="9b855-128">Callers must set the variable to <code>null</code>, and examine the value only if this method returns <code>false</code>.</span></span></param>
        <summary>
            <span data-ttu-id="9b855-129">Bestimmt, ob das angegebene <see cref="T:Microsoft.Azure.KeyVault.WebKey.JsonWebKey" /> Instanz enthält Werte, die Eigenschaften, die den öffentlichen Schlüssel darstellen.</span><span class="sxs-lookup"><span data-stu-id="9b855-129">Determines if the specified <see cref="T:Microsoft.Azure.KeyVault.WebKey.JsonWebKey" /> instance contains values at properties that represent the public key.</span></span> 
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <para><span data-ttu-id="9b855-130">Wenn alle erforderliche public Key Eigenschaften (für den Typ des Schlüssels) in der Instanz angegeben sind, muss die Methode zurück.</span><span class="sxs-lookup"><span data-stu-id="9b855-130">If all required public key properties (for the key type) are specified in the instance, the method must return</span></span>
            <span data-ttu-id="9b855-131"><code>true</code>und es keine Änderungen der <paramref name="missingProps" /> Parameter.</span><span class="sxs-lookup"><span data-stu-id="9b855-131"><code>true</code> and not modify the <paramref name="missingProps" /> parameter.</span></span></para>
        <para><span data-ttu-id="9b855-132">Wenn einige public Key-Eigenschaft nicht vorhanden ist, muss die Methode zurückgeben <code>false</code> und legen Sie <paramref name="missingProps" /> mit einem Wert – in der Regel eine <see cref="T:System.Collections.Generic.List`1" /> -alle fehlenden Eigenschaften enthält.</span><span class="sxs-lookup"><span data-stu-id="9b855-132">If some public key property is missing, the method must return <code>false</code> and set <paramref name="missingProps" /> with a value - typically a <see cref="T:System.Collections.Generic.List`1" /> - containing all missing properties.</span></span></para>
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
            <span data-ttu-id="9b855-133">Gibt an, ob der Typ des Schlüssels, der von diesem Objekt überprüft Algorithmen für öffentliche Schlüssel unterstützt.</span><span class="sxs-lookup"><span data-stu-id="9b855-133">Tells if the type of key verified by this object supports public key algorithms.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
        <code><span data-ttu-id="9b855-134">true</span><span class="sxs-lookup"><span data-stu-id="9b855-134">true</span></span></code>
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
        <param name="webKey"><span data-ttu-id="9b855-135">Die Instanz zu überprüfen.</span><span class="sxs-lookup"><span data-stu-id="9b855-135">The instance to verify.</span></span></param>
        <param name="errorMsg"><span data-ttu-id="9b855-136">Ein Verweis auf eine Variable, die eine Fehlermeldung enthält.</span><span class="sxs-lookup"><span data-stu-id="9b855-136">A reference to a variable that will contain an error message.</span></span> <span data-ttu-id="9b855-137">Aufrufer müssen die Variable festlegen, um <code>null</code>, und überprüfen Sie den Wert nur, wenn diese Methode gibt <code>false</code>.</span><span class="sxs-lookup"><span data-stu-id="9b855-137">Callers must set the variable to <code>null</code>, and examine the value only if this method returns <code>false</code>.</span></span></param>
        <summary>
            <span data-ttu-id="9b855-138">Bestimmt, ob das angegebene <see cref="T:Microsoft.Azure.KeyVault.WebKey.JsonWebKey" /> Instanz einen möglicherweise gültigen öffentlichen Schlüssel enthält (siehe "Hinweise").</span><span class="sxs-lookup"><span data-stu-id="9b855-138">Determines if the specified <see cref="T:Microsoft.Azure.KeyVault.WebKey.JsonWebKey" /> instance contains a possibly valid public key (see remarks).</span></span> 
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <para><span data-ttu-id="9b855-139">Da einen Schlüssel vollständig überprüft werden Unfeasable Anteil der Speicherressourcen erfordern möglicherweise, hat diese Methode nur für offensichtlich Probleme zu überprüfen.</span><span class="sxs-lookup"><span data-stu-id="9b855-139">Because fully validating a key may require unfeasable amount of resources, this method only has to check for obvious issues.</span></span> <span data-ttu-id="9b855-140">Als Richtlinie sagen wir, dass der Code nur offensichtlich Probleme überprüft, ob sie in konstanter Zeit ausgeführt wird.</span><span class="sxs-lookup"><span data-stu-id="9b855-140">As a guideline, we say that the code only verifies obvious issues if it runs in constant time.</span></span>
            <span data-ttu-id="9b855-141">Ist es perfekt geeignet für in einer Implementierung, geschieht nichts und einfach return <code>true</code>.</span><span class="sxs-lookup"><span data-stu-id="9b855-141">It's perfectly valid for implementors to do nothing and simply return <code>true</code>.</span></span></para>
        <para><span data-ttu-id="9b855-142">Diese Methode setzt voraus, dass <see cref="M:Microsoft.Azure.KeyVault.WebKey.JsonWebKeyVerifier.IsPublicKeyComplete(Microsoft.Azure.KeyVault.WebKey.JsonWebKey,System.Collections.Generic.ICollection{System.String}@)" /> aufgerufen und zurückgegeben wurde <code>true</code>.</span><span class="sxs-lookup"><span data-stu-id="9b855-142">This method assumes that <see cref="M:Microsoft.Azure.KeyVault.WebKey.JsonWebKeyVerifier.IsPublicKeyComplete(Microsoft.Azure.KeyVault.WebKey.JsonWebKey,System.Collections.Generic.ICollection{System.String}@)" /> was called and returned <code>true</code>.</span></span> <span data-ttu-id="9b855-143">Es ist nicht auf das Vorhandensein des erforderlichen Eigenschaften erneut testen.</span><span class="sxs-lookup"><span data-stu-id="9b855-143">It doesn't test again for the presence of required properties.</span></span> <span data-ttu-id="9b855-144">Es auslösen <see cref="T:System.NullReferenceException" /> , wenn der Aufrufer finden Sie unter nicht <see cref="M:Microsoft.Azure.KeyVault.WebKey.JsonWebKeyVerifier.IsPublicKeyComplete(Microsoft.Azure.KeyVault.WebKey.JsonWebKey,System.Collections.Generic.ICollection{System.String}@)" /> zurückgeben <code>true</code> erste.</span><span class="sxs-lookup"><span data-stu-id="9b855-144">It may throw <see cref="T:System.NullReferenceException" /> if the caller doesn't see <see cref="M:Microsoft.Azure.KeyVault.WebKey.JsonWebKeyVerifier.IsPublicKeyComplete(Microsoft.Azure.KeyVault.WebKey.JsonWebKey,System.Collections.Generic.ICollection{System.String}@)" /> returning <code>true</code> first.</span></span></para>
        <para><span data-ttu-id="9b855-145">Findet der Valiation Code kein Problem, muss diese Methode zurückgeben <code>true</code> ohne Ändern des Werts eines <paramref name="errorMsg" />.</span><span class="sxs-lookup"><span data-stu-id="9b855-145">If the valiation code finds no issue, this method must return <code>true</code> without modifying the value of <paramref name="errorMsg" />.</span></span></para>
        <para><span data-ttu-id="9b855-146">Wenn ein Problem gefunden wird, muss diese Methode zurückgeben <code>false</code> , und teilen Sie die Informationen in den <paramref name="errorMsg" /> Parameter.</span><span class="sxs-lookup"><span data-stu-id="9b855-146">If some issue is found, this method must return <code>false</code> and tell more details in the <paramref name="errorMsg" /> parameter.</span></span></para>
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
        <param name="webKey"><span data-ttu-id="9b855-147">Die Instanz zu überprüfen.</span><span class="sxs-lookup"><span data-stu-id="9b855-147">The instance to verify.</span></span></param>
        <param name="missingProps"><span data-ttu-id="9b855-148">Ein Verweis auf eine Variable, die die Liste der fehlenden Eigenschaften informiert.</span><span class="sxs-lookup"><span data-stu-id="9b855-148">A reference to a variable that tells the list of missing properties.</span></span> <span data-ttu-id="9b855-149">Aufrufer müssen die Variable festlegen, um <code>null</code>, und überprüfen Sie den Wert nur, wenn diese Methode gibt <code>false</code>.</span><span class="sxs-lookup"><span data-stu-id="9b855-149">Callers must set the variable to <code>null</code>, and examine the value only if this method returns <code>false</code>.</span></span></param>
        <summary>
            <span data-ttu-id="9b855-150">Bestimmt, ob das angegebene <see cref="T:Microsoft.Azure.KeyVault.WebKey.JsonWebKey" /> Instanz enthält Werte, die Eigenschaften, die für den geheimen Schlüssel darstellen.</span><span class="sxs-lookup"><span data-stu-id="9b855-150">Determines if the specified <see cref="T:Microsoft.Azure.KeyVault.WebKey.JsonWebKey" /> instance contains values at properties that represent the secret key.</span></span> 
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <para><span data-ttu-id="9b855-151">Wenn alle erforderliche für den geheimen Schlüssel Eigenschaften (für den Typ des Schlüssels) in der Instanz angegeben sind, muss die Methode zurück.</span><span class="sxs-lookup"><span data-stu-id="9b855-151">If all required secret key properties (for the key type) are specified in the instance, the method must return</span></span>
            <span data-ttu-id="9b855-152"><code>true</code>und es keine Änderungen der <paramref name="missingProps" /> Parameter.</span><span class="sxs-lookup"><span data-stu-id="9b855-152"><code>true</code> and not modify the <paramref name="missingProps" /> parameter.</span></span></para>
        <para><span data-ttu-id="9b855-153">Wenn eine bestimmte Eigenschaft nicht vorhanden ist, muss die Methode zurückgeben <code>false</code> und legen Sie <paramref name="missingProps" /> in einen Wert – in der Regel eine <see cref="T:System.Collections.Generic.List`1" /> -alle fehlenden Eigenschaften enthält.</span><span class="sxs-lookup"><span data-stu-id="9b855-153">If some property is missing, the method must return <code>false</code> and set <paramref name="missingProps" /> to a value - typically a <see cref="T:System.Collections.Generic.List`1" /> - containing all missing properties.</span></span></para>
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
        <param name="webKey"><span data-ttu-id="9b855-154">Die Instanz zu überprüfen.</span><span class="sxs-lookup"><span data-stu-id="9b855-154">The instance to verify.</span></span></param>
        <param name="errorMsg"><span data-ttu-id="9b855-155">Ein Verweis auf eine Variable, die eine Fehlermeldung enthält.</span><span class="sxs-lookup"><span data-stu-id="9b855-155">A reference to a variable that will contain an error message.</span></span> <span data-ttu-id="9b855-156">Aufrufer müssen die Variable festlegen, um <code>null</code>, und überprüfen Sie den Wert nur, wenn diese Methode gibt <code>false</code>.</span><span class="sxs-lookup"><span data-stu-id="9b855-156">Callers must set the variable to <code>null</code>, and examine the value only if this method returns <code>false</code>.</span></span></param>
        <summary>
            <span data-ttu-id="9b855-157">Bestimmt, ob das angegebene <see cref="T:Microsoft.Azure.KeyVault.WebKey.JsonWebKey" /> Instanz enthält möglicherweise gültigen für den geheimen Schlüssel (siehe "Hinweise").</span><span class="sxs-lookup"><span data-stu-id="9b855-157">Determines if the specified <see cref="T:Microsoft.Azure.KeyVault.WebKey.JsonWebKey" /> instance contains a possibly valid secret key (see remarks).</span></span> 
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <para><span data-ttu-id="9b855-158">Da einen Schlüssel vollständig überprüft werden Unfeasable Anteil der Speicherressourcen erfordern möglicherweise, hat diese Methode nur für offensichtlich Probleme zu überprüfen.</span><span class="sxs-lookup"><span data-stu-id="9b855-158">Because fully validating a key may require unfeasable amount of resources, this method only has to check for obvious issues.</span></span> <span data-ttu-id="9b855-159">Als Richtlinie sagen wir, dass der Code nur offensichtlich Probleme überprüft, ob sie in konstanter Zeit ausgeführt wird.</span><span class="sxs-lookup"><span data-stu-id="9b855-159">As a guideline, we say that the code only verifies obvious issues if it runs in constant time.</span></span>
            <span data-ttu-id="9b855-160">Ist es perfekt geeignet für in einer Implementierung, geschieht nichts und einfach return <code>true</code>.</span><span class="sxs-lookup"><span data-stu-id="9b855-160">It's perfectly valid for implementors to do nothing and simply return <code>true</code>.</span></span></para>
        <para><span data-ttu-id="9b855-161">Diese Methode setzt voraus, dass <see cref="M:Microsoft.Azure.KeyVault.WebKey.JsonWebKeyVerifier.IsSecretKeyComplete(Microsoft.Azure.KeyVault.WebKey.JsonWebKey,System.Collections.Generic.ICollection{System.String}@)" /> aufgerufen und zurückgegeben wurde <code>true</code>.</span><span class="sxs-lookup"><span data-stu-id="9b855-161">This method assumes that <see cref="M:Microsoft.Azure.KeyVault.WebKey.JsonWebKeyVerifier.IsSecretKeyComplete(Microsoft.Azure.KeyVault.WebKey.JsonWebKey,System.Collections.Generic.ICollection{System.String}@)" /> was called and returned <code>true</code>.</span></span> <span data-ttu-id="9b855-162">Es ist nicht auf das Vorhandensein des erforderlichen Eigenschaften erneut testen.</span><span class="sxs-lookup"><span data-stu-id="9b855-162">It doesn't test again for the presence of required properties.</span></span> <span data-ttu-id="9b855-163">Es auslösen <see cref="T:System.NullReferenceException" /> , wenn der Aufrufer finden Sie unter nicht <see cref="M:Microsoft.Azure.KeyVault.WebKey.JsonWebKeyVerifier.IsSecretKeyComplete(Microsoft.Azure.KeyVault.WebKey.JsonWebKey,System.Collections.Generic.ICollection{System.String}@)" /> zurückgeben <code>true</code> erste.</span><span class="sxs-lookup"><span data-stu-id="9b855-163">It may throw <see cref="T:System.NullReferenceException" /> if the caller doesn't see <see cref="M:Microsoft.Azure.KeyVault.WebKey.JsonWebKeyVerifier.IsSecretKeyComplete(Microsoft.Azure.KeyVault.WebKey.JsonWebKey,System.Collections.Generic.ICollection{System.String}@)" /> returning <code>true</code> first.</span></span></para>
        <para><span data-ttu-id="9b855-164">Findet der Valiation Code kein Problem, muss diese Methode zurückgeben <code>true</code> ohne Ändern des Werts eines <paramref name="errorMsg" />.</span><span class="sxs-lookup"><span data-stu-id="9b855-164">If the valiation code finds no issue, this method must return <code>true</code> without modifying the value of <paramref name="errorMsg" />.</span></span></para>
        <para><span data-ttu-id="9b855-165">Wenn ein Problem gefunden wird, muss diese Methode zurückgeben <code>false</code> , und teilen Sie die Informationen in den <paramref name="errorMsg" /> Parameter.</span><span class="sxs-lookup"><span data-stu-id="9b855-165">If some issue is found, this method must return <code>false</code> and tell more details in the <paramref name="errorMsg" /> parameter.</span></span></para>
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
        <param name="webKey"><span data-ttu-id="9b855-166">Die Instanz zu überprüfen.</span><span class="sxs-lookup"><span data-stu-id="9b855-166">The instance to verify.</span></span></param>
        <param name="missingProps"><span data-ttu-id="9b855-167">Ein Verweis auf eine Variable, die die Liste der fehlenden Eigenschaften informiert.</span><span class="sxs-lookup"><span data-stu-id="9b855-167">A reference to a variable that tells the list of missing properties.</span></span> <span data-ttu-id="9b855-168">Aufrufer müssen die Variable festlegen, um <code>null</code>, und überprüfen Sie den Wert nur, wenn diese Methode gibt <code>false</code>.</span><span class="sxs-lookup"><span data-stu-id="9b855-168">Callers must set the variable to <code>null</code>, and examine the value only if this method returns <code>false</code>.</span></span></param>
        <summary>
            <span data-ttu-id="9b855-169">Bestimmt, ob das angegebene <see cref="T:Microsoft.Azure.KeyVault.WebKey.JsonWebKey" /> Instanz enthält Werte, die auf Eigenschaften, die den symmetrischen Schlüssel darstellen.</span><span class="sxs-lookup"><span data-stu-id="9b855-169">Determines if the specified <see cref="T:Microsoft.Azure.KeyVault.WebKey.JsonWebKey" /> instance contains values at properties that represent the symmetric key.</span></span> 
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <para><span data-ttu-id="9b855-170">Wenn alle erforderliche symmetrischen Schlüssel Eigenschaften (für den Typ des Schlüssels) in der Instanz angegeben sind, muss die Methode zurück.</span><span class="sxs-lookup"><span data-stu-id="9b855-170">If all required symmetric key properties (for the key type) are specified in the instance, the method must return</span></span>
            <span data-ttu-id="9b855-171"><code>true</code>und es keine Änderungen der <paramref name="missingProps" /> Parameter.</span><span class="sxs-lookup"><span data-stu-id="9b855-171"><code>true</code> and not modify the <paramref name="missingProps" /> parameter.</span></span></para>
        <para><span data-ttu-id="9b855-172">Wenn eine bestimmte Eigenschaft nicht vorhanden ist, muss die Methode zurückgeben <code>false</code> und legen Sie <paramref name="missingProps" /> in einen Wert – in der Regel eine <see cref="T:System.Collections.Generic.List`1" /> -alle fehlenden Eigenschaften enthält.</span><span class="sxs-lookup"><span data-stu-id="9b855-172">If some property is missing, the method must return <code>false</code> and set <paramref name="missingProps" /> to a value - typically a <see cref="T:System.Collections.Generic.List`1" /> - containing all missing properties.</span></span></para>
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
            <span data-ttu-id="9b855-173">Gibt an, ob der Typ des Schlüssels, der von diesem Objekt überprüft Algorithmen mit symmetrische Schlüssel unterstützt.</span><span class="sxs-lookup"><span data-stu-id="9b855-173">Tells if the type of key verified by this object supports symmetric key algorithms.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
        <code><span data-ttu-id="9b855-174">true</span><span class="sxs-lookup"><span data-stu-id="9b855-174">true</span></span></code>
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
        <param name="webKey"><span data-ttu-id="9b855-175">Die Instanz zu überprüfen.</span><span class="sxs-lookup"><span data-stu-id="9b855-175">The instance to verify.</span></span></param>
        <param name="errorMsg"><span data-ttu-id="9b855-176">Ein Verweis auf eine Variable, die eine Fehlermeldung enthält.</span><span class="sxs-lookup"><span data-stu-id="9b855-176">A reference to a variable that will contain an error message.</span></span> <span data-ttu-id="9b855-177">Aufrufer müssen die Variable festlegen, um <code>null</code>, und überprüfen Sie den Wert nur, wenn diese Methode gibt <code>false</code>.</span><span class="sxs-lookup"><span data-stu-id="9b855-177">Callers must set the variable to <code>null</code>, and examine the value only if this method returns <code>false</code>.</span></span></param>
        <summary>
            <span data-ttu-id="9b855-178">Bestimmt, ob das angegebene <see cref="T:Microsoft.Azure.KeyVault.WebKey.JsonWebKey" /> Instanz einen möglicherweise gültigen symmetrischen Schlüssel enthält (siehe "Hinweise").</span><span class="sxs-lookup"><span data-stu-id="9b855-178">Determines if the specified <see cref="T:Microsoft.Azure.KeyVault.WebKey.JsonWebKey" /> instance contains a possibly valid symmetric key (see remarks).</span></span> 
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <para><span data-ttu-id="9b855-179">Da einen Schlüssel vollständig überprüft werden Unfeasable Anteil der Speicherressourcen erfordern möglicherweise, hat diese Methode nur für offensichtlich Probleme zu überprüfen.</span><span class="sxs-lookup"><span data-stu-id="9b855-179">Because fully validating a key may require unfeasable amount of resources, this method only has to check for obvious issues.</span></span> <span data-ttu-id="9b855-180">Als Richtlinie sagen wir, dass der Code nur offensichtlich Probleme überprüft, ob sie in konstanter Zeit ausgeführt wird.</span><span class="sxs-lookup"><span data-stu-id="9b855-180">As a guideline, we say that the code only verifies obvious issues if it runs in constant time.</span></span>
            <span data-ttu-id="9b855-181">Ist es perfekt geeignet für in einer Implementierung, geschieht nichts und einfach return <code>true</code>.</span><span class="sxs-lookup"><span data-stu-id="9b855-181">It's perfectly valid for implementors to do nothing and simply return <code>true</code>.</span></span></para>
        <para><span data-ttu-id="9b855-182">Diese Methode setzt voraus, dass <see cref="M:Microsoft.Azure.KeyVault.WebKey.JsonWebKeyVerifier.IsSymmetricKeyComplete(Microsoft.Azure.KeyVault.WebKey.JsonWebKey,System.Collections.Generic.ICollection{System.String}@)" /> aufgerufen und zurückgegeben wurde <code>true</code>.</span><span class="sxs-lookup"><span data-stu-id="9b855-182">This method assumes that <see cref="M:Microsoft.Azure.KeyVault.WebKey.JsonWebKeyVerifier.IsSymmetricKeyComplete(Microsoft.Azure.KeyVault.WebKey.JsonWebKey,System.Collections.Generic.ICollection{System.String}@)" /> was called and returned <code>true</code>.</span></span> <span data-ttu-id="9b855-183">Es ist nicht auf das Vorhandensein des erforderlichen Eigenschaften erneut testen.</span><span class="sxs-lookup"><span data-stu-id="9b855-183">It doesn't test again for the presence of required properties.</span></span> <span data-ttu-id="9b855-184">Es auslösen <see cref="T:System.NullReferenceException" /> , wenn der Aufrufer finden Sie unter nicht <see cref="M:Microsoft.Azure.KeyVault.WebKey.JsonWebKeyVerifier.IsSymmetricKeyComplete(Microsoft.Azure.KeyVault.WebKey.JsonWebKey,System.Collections.Generic.ICollection{System.String}@)" /> zurückgeben <code>true</code> erste.</span><span class="sxs-lookup"><span data-stu-id="9b855-184">It may throw <see cref="T:System.NullReferenceException" /> if the caller doesn't see <see cref="M:Microsoft.Azure.KeyVault.WebKey.JsonWebKeyVerifier.IsSymmetricKeyComplete(Microsoft.Azure.KeyVault.WebKey.JsonWebKey,System.Collections.Generic.ICollection{System.String}@)" /> returning <code>true</code> first.</span></span></para>
        <para><span data-ttu-id="9b855-185">Findet der Valiation Code kein Problem, muss diese Methode zurückgeben <code>true</code> ohne Ändern des Werts eines <paramref name="errorMsg" />.</span><span class="sxs-lookup"><span data-stu-id="9b855-185">If the valiation code finds no issue, this method must return <code>true</code> without modifying the value of <paramref name="errorMsg" />.</span></span></para>
        <para><span data-ttu-id="9b855-186">Wenn ein Problem gefunden wird, muss diese Methode zurückgeben <code>false</code> , und teilen Sie die Informationen in den <paramref name="errorMsg" /> Parameter.</span><span class="sxs-lookup"><span data-stu-id="9b855-186">If some issue is found, this method must return <code>false</code> and tell more details in the <paramref name="errorMsg" /> parameter.</span></span></para>
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
            <span data-ttu-id="9b855-187">Gibt an, welche Art von Schlüssel für diese Prüfung gilt.</span><span class="sxs-lookup"><span data-stu-id="9b855-187">Indicates which type of key this verifier applies to.</span></span>
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
        <param name="verifier"><span data-ttu-id="9b855-188">Die Überprüfung zu registrieren.</span><span class="sxs-lookup"><span data-stu-id="9b855-188">The verifier to register.</span></span></param>
        <summary>
            <span data-ttu-id="9b855-189">Registriert eine Prüfung für einen <see cref="P:Microsoft.Azure.KeyVault.WebKey.JsonWebKeyVerifier.Kty" /> Wert.</span><span class="sxs-lookup"><span data-stu-id="9b855-189">Registers a verifier for a <see cref="P:Microsoft.Azure.KeyVault.WebKey.JsonWebKeyVerifier.Kty" /> value.</span></span>
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
            <span data-ttu-id="9b855-190">Hilfsmethode, die Zeichenfolgenwerte mit doppelten Anführungszeichen umgeben.</span><span class="sxs-lookup"><span data-stu-id="9b855-190">Helper method that surrounds string values with double-quotes.</span></span> 
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <code><span data-ttu-id="9b855-191">"Foo", "Balken"</span><span class="sxs-lookup"><span data-stu-id="9b855-191">"Foo", "Bar"</span></span></code>
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
        <param name="value"><span data-ttu-id="9b855-192">Das Array, um zu überprüfen.</span><span class="sxs-lookup"><span data-stu-id="9b855-192">The array to validate.</span></span></param>
        <param name="name"><span data-ttu-id="9b855-193">Der Arrayname, der verwendet werden kann, um Fehlermeldungen zu erstellen.</span><span class="sxs-lookup"><span data-stu-id="9b855-193">The array name, which may be used to build error messages.</span></span></param>
        <param name="requiredSize"><span data-ttu-id="9b855-194">Die erforderliche Größe in Bytes.</span><span class="sxs-lookup"><span data-stu-id="9b855-194">The required size, in bytes.</span></span></param>
        <param name="errorMsg"><span data-ttu-id="9b855-195">Ein Verweis auf eine Variable, die die Fehlermeldung enthält.</span><span class="sxs-lookup"><span data-stu-id="9b855-195">A reference to a variable that will contain the error message.</span></span> <span data-ttu-id="9b855-196">Dies wird nur festgelegt, wenn die-Methode zurückgibt <code>false</code>.</span><span class="sxs-lookup"><span data-stu-id="9b855-196">This is only set if the method returns <code>false</code>.</span></span></param>
        <summary>
            <span data-ttu-id="9b855-197">Hilfsmethode, die die Größe eines Bytearrays überprüft.</span><span class="sxs-lookup"><span data-stu-id="9b855-197">Helper method that validates the size of a byte array.</span></span>
            </summary>
        <returns>
          <span data-ttu-id="9b855-198"><code>true</code>Wenn das Array eine gültige Größe hat; <code>false otherwise</code>.</span><span class="sxs-lookup"><span data-stu-id="9b855-198"><code>true</code> if the array has a valid size; <code>false otherwise</code>.</span></span></returns>
        <remarks>To be added.</remarks>
        <para><span data-ttu-id="9b855-199">Ein gültiges Array erfüllt folgende Kriterien:</span><span class="sxs-lookup"><span data-stu-id="9b855-199">A valid array meets the following criteria:</span></span></para>
        <list type="bullet">
          <item>
            <description><span data-ttu-id="9b855-200">ist kein <code>null</code>;</span><span class="sxs-lookup"><span data-stu-id="9b855-200">is not <code>null</code>;</span></span></description>
          </item>
          <item>
            <description><span data-ttu-id="9b855-201">die Länge beträgt mindestens <paramref name="requiredSize" />; und</span><span class="sxs-lookup"><span data-stu-id="9b855-201">the length is at least <paramref name="requiredSize" />; and</span></span></description>
          </item>
          <item>
            <description><span data-ttu-id="9b855-202">übermäßige führende Bytes werden Nullen.</span><span class="sxs-lookup"><span data-stu-id="9b855-202">excess leading bytes are all zeros.</span></span></description>
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
        <param name="webKey"><span data-ttu-id="9b855-203">Die Instanz zu überprüfen.</span><span class="sxs-lookup"><span data-stu-id="9b855-203">The instance to verify.</span></span></param>
        <param name="options"><span data-ttu-id="9b855-204">Gibt an, wie ist eine Überprüfung der verhält.</span><span class="sxs-lookup"><span data-stu-id="9b855-204">Tells how verification is to behave.</span></span></param>
        <param name="error"><span data-ttu-id="9b855-205">Ein Verweis auf eine Variable, die die Fehlermeldung mitteilt, wenn die Überprüfung fehlschlägt.</span><span class="sxs-lookup"><span data-stu-id="9b855-205">A reference to a variable that will tell the error message, if verification fails.</span></span> <span data-ttu-id="9b855-206">Dies wird nur festgelegt, wenn die-Methode zurückgibt <code>false</code>.</span><span class="sxs-lookup"><span data-stu-id="9b855-206">This is only set if the method returns <code>false</code>.</span></span> <span data-ttu-id="9b855-207">Wenn die-Methode zurückgibt <code>true</code> oder eine Ausnahme auslöst, die <paramref name="error" /> nicht anzeigen, die geändert wird.</span><span class="sxs-lookup"><span data-stu-id="9b855-207">If the method returns <code>true</code> or throws an exception, the <paramref name="error" /> will not me modified.</span></span></param>
        <summary>
            <span data-ttu-id="9b855-208">Überprüft die angegebene JsonWebKey-Instanz an.</span><span class="sxs-lookup"><span data-stu-id="9b855-208">Verifies the specified JsonWebKey instance.</span></span> 
            </summary>
        <returns>
          <span data-ttu-id="9b855-209"><code>true</code>Wenn der Wert JsonWebKey gültig ist <code>false otherwise</code>.</span><span class="sxs-lookup"><span data-stu-id="9b855-209"><code>true</code> if the JsonWebKey value is valid, <code>false otherwise</code>.</span></span></returns>
        <remarks>To be added.</remarks>
        <para><span data-ttu-id="9b855-210">Zuerst daraufhin überprüft die <see cref="P:Microsoft.Azure.KeyVault.WebKey.JsonWebKey.Kty" /> Eigenschaft, um eine Instanz Verifier auszuwählen (Weitere Informationen finden Sie unter der <see cref="M:Microsoft.Azure.KeyVault.WebKey.JsonWebKeyVerifier.Register(Microsoft.Azure.KeyVault.WebKey.JsonWebKeyVerifier)" /> Methode).</span><span class="sxs-lookup"><span data-stu-id="9b855-210">Verification first examines the <see cref="P:Microsoft.Azure.KeyVault.WebKey.JsonWebKey.Kty" /> property to select a verifier instance (for more information, see the <see cref="M:Microsoft.Azure.KeyVault.WebKey.JsonWebKeyVerifier.Register(Microsoft.Azure.KeyVault.WebKey.JsonWebKeyVerifier)" /> method).</span></span> <span data-ttu-id="9b855-211">Wenn eine Prüfung gefunden wird, wird er verwendet zum Überprüfen, ob der Schlüssel mit dem entsprechenden Schlüsseltyp entspricht.</span><span class="sxs-lookup"><span data-stu-id="9b855-211">If a verifier is found, it's used to check if the key conforms to the corresponding key type.</span></span></para>
        <exception cref="T:System.ArgumentNullException"><span data-ttu-id="9b855-212">Wenn die <paramref name="webKey" /> -Parameter ist null.</span><span class="sxs-lookup"><span data-stu-id="9b855-212">If the <paramref name="webKey" /> parameter is null.</span></span></exception>
        <exception cref="T:System.ArgumentException"><span data-ttu-id="9b855-213">Wenn die <paramref name="options" /> Parameter enthält ungültige Optionen.</span><span class="sxs-lookup"><span data-stu-id="9b855-213">If the <paramref name="options" /> parameter contains invalid options.</span></span></exception>
        <exception cref="T:Microsoft.Azure.KeyVault.WebKey.JsonWebKeyVerificationException"><span data-ttu-id="9b855-214">Das Objekt JsonWebKey ist "Invalid" und "die Option <see cref="F:Microsoft.Azure.KeyVault.WebKey.JsonWebKeyVerifier.Options.ThrowException" /> angegeben wurde.</span><span class="sxs-lookup"><span data-stu-id="9b855-214">If the JsonWebKey object is invalid and the option <see cref="F:Microsoft.Azure.KeyVault.WebKey.JsonWebKeyVerifier.Options.ThrowException" /> was specified.</span></span></exception>
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
            <span data-ttu-id="9b855-215">Überprüft die angegebene JsonWebKey-Instanz gemäß <see cref="P:Microsoft.Azure.KeyVault.WebKey.JsonWebKey.Kty" />.</span><span class="sxs-lookup"><span data-stu-id="9b855-215">Verifies the specified JsonWebKey instance according to <see cref="P:Microsoft.Azure.KeyVault.WebKey.JsonWebKey.Kty" />.</span></span>
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