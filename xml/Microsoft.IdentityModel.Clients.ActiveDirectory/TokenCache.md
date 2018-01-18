<Type Name="TokenCache" FullName="Microsoft.IdentityModel.Clients.ActiveDirectory.TokenCache">
  <TypeSignature Language="C#" Value="public class TokenCache" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi TokenCache extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.IdentityModel.Clients.ActiveDirectory.TokenCache" />
  <TypeSignature Language="VB.NET" Value="Public Class TokenCache" />
  <TypeSignature Language="F#" Value="type TokenCache = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.IdentityModel.Clients.ActiveDirectory</AssemblyName>
    <AssemblyVersion>3.16.0.14</AssemblyVersion>
    <AssemblyVersion>3.17.3.35304</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="f119d-101">Cacheklasse, die vom Token <see cref="T:Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationContext" /> Zugriff speichern und Aktualisieren von Token.</span><span class="sxs-lookup"><span data-stu-id="f119d-101">Token cache class used by <see cref="T:Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationContext" /> to store access and refresh tokens.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public TokenCache ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.IdentityModel.Clients.ActiveDirectory.TokenCache.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.IdentityModel.Clients.ActiveDirectory</AssemblyName>
        <AssemblyVersion>3.16.0.14</AssemblyVersion>
        <AssemblyVersion>3.17.3.35304</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="f119d-102">Standardkonstruktor</span><span class="sxs-lookup"><span data-stu-id="f119d-102">Default constructor.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public TokenCache (byte[] state);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(unsigned int8[] state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.IdentityModel.Clients.ActiveDirectory.TokenCache.#ctor(System.Byte[])" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (state As Byte())" />
      <MemberSignature Language="F#" Value="new Microsoft.IdentityModel.Clients.ActiveDirectory.TokenCache : byte[] -&gt; Microsoft.IdentityModel.Clients.ActiveDirectory.TokenCache" Usage="new Microsoft.IdentityModel.Clients.ActiveDirectory.TokenCache state" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.IdentityModel.Clients.ActiveDirectory</AssemblyName>
        <AssemblyVersion>3.16.0.14</AssemblyVersion>
        <AssemblyVersion>3.17.3.35304</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="state" Type="System.Byte[]" />
      </Parameters>
      <Docs>
        <param name="state">To be added.</param>
        <summary>
            <span data-ttu-id="f119d-103">Status des Caches empfangen Konstruktor</span><span class="sxs-lookup"><span data-stu-id="f119d-103">Constructor receiving state of the cache</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AfterAccess">
      <MemberSignature Language="C#" Value="public Microsoft.IdentityModel.Clients.ActiveDirectory.TokenCache.TokenCacheNotification AfterAccess { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.IdentityModel.Clients.ActiveDirectory.TokenCache/TokenCacheNotification AfterAccess" />
      <MemberSignature Language="DocId" Value="P:Microsoft.IdentityModel.Clients.ActiveDirectory.TokenCache.AfterAccess" />
      <MemberSignature Language="VB.NET" Value="Public Property AfterAccess As TokenCache.TokenCacheNotification" />
      <MemberSignature Language="F#" Value="member this.AfterAccess : Microsoft.IdentityModel.Clients.ActiveDirectory.TokenCache.TokenCacheNotification with get, set" Usage="Microsoft.IdentityModel.Clients.ActiveDirectory.TokenCache.AfterAccess" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.IdentityModel.Clients.ActiveDirectory</AssemblyName>
        <AssemblyVersion>3.16.0.14</AssemblyVersion>
        <AssemblyVersion>3.17.3.35304</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.IdentityModel.Clients.ActiveDirectory.TokenCache+TokenCacheNotification</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="f119d-104">Benachrichtigungsmethode wird aufgerufen, nachdem eine Bibliotheksmethode auf den Cache zugreift.</span><span class="sxs-lookup"><span data-stu-id="f119d-104">Notification method called after any library method accesses the cache.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeforeAccess">
      <MemberSignature Language="C#" Value="public Microsoft.IdentityModel.Clients.ActiveDirectory.TokenCache.TokenCacheNotification BeforeAccess { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.IdentityModel.Clients.ActiveDirectory.TokenCache/TokenCacheNotification BeforeAccess" />
      <MemberSignature Language="DocId" Value="P:Microsoft.IdentityModel.Clients.ActiveDirectory.TokenCache.BeforeAccess" />
      <MemberSignature Language="VB.NET" Value="Public Property BeforeAccess As TokenCache.TokenCacheNotification" />
      <MemberSignature Language="F#" Value="member this.BeforeAccess : Microsoft.IdentityModel.Clients.ActiveDirectory.TokenCache.TokenCacheNotification with get, set" Usage="Microsoft.IdentityModel.Clients.ActiveDirectory.TokenCache.BeforeAccess" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.IdentityModel.Clients.ActiveDirectory</AssemblyName>
        <AssemblyVersion>3.16.0.14</AssemblyVersion>
        <AssemblyVersion>3.17.3.35304</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.IdentityModel.Clients.ActiveDirectory.TokenCache+TokenCacheNotification</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="f119d-105">Benachrichtigungsmethode wird aufgerufen, bevor eine Bibliotheksmethode auf den Cache zugreift.</span><span class="sxs-lookup"><span data-stu-id="f119d-105">Notification method called before any library method accesses the cache.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeforeWrite">
      <MemberSignature Language="C#" Value="public Microsoft.IdentityModel.Clients.ActiveDirectory.TokenCache.TokenCacheNotification BeforeWrite { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.IdentityModel.Clients.ActiveDirectory.TokenCache/TokenCacheNotification BeforeWrite" />
      <MemberSignature Language="DocId" Value="P:Microsoft.IdentityModel.Clients.ActiveDirectory.TokenCache.BeforeWrite" />
      <MemberSignature Language="VB.NET" Value="Public Property BeforeWrite As TokenCache.TokenCacheNotification" />
      <MemberSignature Language="F#" Value="member this.BeforeWrite : Microsoft.IdentityModel.Clients.ActiveDirectory.TokenCache.TokenCacheNotification with get, set" Usage="Microsoft.IdentityModel.Clients.ActiveDirectory.TokenCache.BeforeWrite" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.IdentityModel.Clients.ActiveDirectory</AssemblyName>
        <AssemblyVersion>3.16.0.14</AssemblyVersion>
        <AssemblyVersion>3.17.3.35304</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.IdentityModel.Clients.ActiveDirectory.TokenCache+TokenCacheNotification</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="f119d-106">Benachrichtigungsmethode wird aufgerufen, bevor eine Bibliotheksmethode in den Cache schreibt.</span><span class="sxs-lookup"><span data-stu-id="f119d-106">Notification method called before any library method writes to the cache.</span></span> <span data-ttu-id="f119d-107">Diese Benachrichtigung kann verwendet werden, laden den Cache-Zustand aus einer Zeile in der Datenbank und Sperren diese Zeile.</span><span class="sxs-lookup"><span data-stu-id="f119d-107">This notification can be used to reload the cache state from a row in database and lock that row.</span></span> <span data-ttu-id="f119d-108">Diese Datenbankzeile kann dann entsperrt werden <see cref="P:Microsoft.IdentityModel.Clients.ActiveDirectory.TokenCache.AfterAccess" /> Benachrichtigung.</span><span class="sxs-lookup"><span data-stu-id="f119d-108">That database row can then be unlocked in <see cref="P:Microsoft.IdentityModel.Clients.ActiveDirectory.TokenCache.AfterAccess" /> notification.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Clear">
      <MemberSignature Language="C#" Value="public virtual void Clear ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Clear() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.IdentityModel.Clients.ActiveDirectory.TokenCache.Clear" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Clear ()" />
      <MemberSignature Language="F#" Value="abstract member Clear : unit -&gt; unit&#xA;override this.Clear : unit -&gt; unit" Usage="tokenCache.Clear " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.IdentityModel.Clients.ActiveDirectory</AssemblyName>
        <AssemblyVersion>3.16.0.14</AssemblyVersion>
        <AssemblyVersion>3.17.3.35304</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="f119d-109">Löscht den Cache durch alle Elemente löschen.</span><span class="sxs-lookup"><span data-stu-id="f119d-109">Clears the cache by deleting all the items.</span></span> <span data-ttu-id="f119d-110">Beachten Sie, dass wenn der Cache den Standardcache freigegeben ist, ist es deaktiviert, alle Instanzen von beeinträchtigen würde <see cref="T:Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationContext" /> die diesen Cache freigeben.</span><span class="sxs-lookup"><span data-stu-id="f119d-110">Note that if the cache is the default shared cache, clearing it would impact all the instances of <see cref="T:Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationContext" /> which share that cache.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Count">
      <MemberSignature Language="C#" Value="public int Count { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 Count" />
      <MemberSignature Language="DocId" Value="P:Microsoft.IdentityModel.Clients.ActiveDirectory.TokenCache.Count" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Count As Integer" />
      <MemberSignature Language="F#" Value="member this.Count : int" Usage="Microsoft.IdentityModel.Clients.ActiveDirectory.TokenCache.Count" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.IdentityModel.Clients.ActiveDirectory</AssemblyName>
        <AssemblyVersion>3.16.0.14</AssemblyVersion>
        <AssemblyVersion>3.17.3.35304</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="f119d-111">Ruft die Nunmber von Elementen im Cache ab.</span><span class="sxs-lookup"><span data-stu-id="f119d-111">Gets the nunmber of items in the cache.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DefaultShared">
      <MemberSignature Language="C#" Value="public static Microsoft.IdentityModel.Clients.ActiveDirectory.TokenCache DefaultShared { get; }" />
      <MemberSignature Language="ILAsm" Value=".property class Microsoft.IdentityModel.Clients.ActiveDirectory.TokenCache DefaultShared" />
      <MemberSignature Language="DocId" Value="P:Microsoft.IdentityModel.Clients.ActiveDirectory.TokenCache.DefaultShared" />
      <MemberSignature Language="VB.NET" Value="Public Shared ReadOnly Property DefaultShared As TokenCache" />
      <MemberSignature Language="F#" Value="member this.DefaultShared : Microsoft.IdentityModel.Clients.ActiveDirectory.TokenCache" Usage="Microsoft.IdentityModel.Clients.ActiveDirectory.TokenCache.DefaultShared" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.IdentityModel.Clients.ActiveDirectory</AssemblyName>
        <AssemblyVersion>3.16.0.14</AssemblyVersion>
        <AssemblyVersion>3.17.3.35304</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.IdentityModel.Clients.ActiveDirectory.TokenCache</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="f119d-112">Statische Tokencache von allen Instanzen AuthenticationContext, die nicht explizit eine Cache-Instanz während der Erstellung bestehen, gemeinsam verwendet werden.</span><span class="sxs-lookup"><span data-stu-id="f119d-112">Static token cache shared by all instances of AuthenticationContext which do not explicitly pass a cache instance during construction.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteItem">
      <MemberSignature Language="C#" Value="public virtual void DeleteItem (Microsoft.IdentityModel.Clients.ActiveDirectory.TokenCacheItem item);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void DeleteItem(class Microsoft.IdentityModel.Clients.ActiveDirectory.TokenCacheItem item) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.IdentityModel.Clients.ActiveDirectory.TokenCache.DeleteItem(Microsoft.IdentityModel.Clients.ActiveDirectory.TokenCacheItem)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub DeleteItem (item As TokenCacheItem)" />
      <MemberSignature Language="F#" Value="abstract member DeleteItem : Microsoft.IdentityModel.Clients.ActiveDirectory.TokenCacheItem -&gt; unit&#xA;override this.DeleteItem : Microsoft.IdentityModel.Clients.ActiveDirectory.TokenCacheItem -&gt; unit" Usage="tokenCache.DeleteItem item" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.IdentityModel.Clients.ActiveDirectory</AssemblyName>
        <AssemblyVersion>3.16.0.14</AssemblyVersion>
        <AssemblyVersion>3.17.3.35304</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="item" Type="Microsoft.IdentityModel.Clients.ActiveDirectory.TokenCacheItem" />
      </Parameters>
      <Docs>
        <param name="item"><span data-ttu-id="f119d-113">Das Element, aus dem Cache löschen</span><span class="sxs-lookup"><span data-stu-id="f119d-113">The item to delete from the cache</span></span></param>
        <summary>
            <span data-ttu-id="f119d-114">Löscht ein Element aus dem Cache.</span><span class="sxs-lookup"><span data-stu-id="f119d-114">Deletes an item from the cache.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Deserialize">
      <MemberSignature Language="C#" Value="public void Deserialize (byte[] state);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void Deserialize(unsigned int8[] state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.IdentityModel.Clients.ActiveDirectory.TokenCache.Deserialize(System.Byte[])" />
      <MemberSignature Language="VB.NET" Value="Public Sub Deserialize (state As Byte())" />
      <MemberSignature Language="F#" Value="member this.Deserialize : byte[] -&gt; unit" Usage="tokenCache.Deserialize state" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.IdentityModel.Clients.ActiveDirectory</AssemblyName>
        <AssemblyVersion>3.16.0.14</AssemblyVersion>
        <AssemblyVersion>3.17.3.35304</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="state" Type="System.Byte[]" />
      </Parameters>
      <Docs>
        <param name="state"><span data-ttu-id="f119d-115">Status des Caches als blob</span><span class="sxs-lookup"><span data-stu-id="f119d-115">State of the cache as a blob</span></span></param>
        <summary>
            <span data-ttu-id="f119d-116">Deserialisiert die Zustand des Caches.</span><span class="sxs-lookup"><span data-stu-id="f119d-116">Deserializes state of the cache.</span></span> <span data-ttu-id="f119d-117">Der Status sollte das Blob, die zuvor durch Aufrufen der Methode Serialize empfangen.</span><span class="sxs-lookup"><span data-stu-id="f119d-117">The state should be the blob received earlier by calling the method Serialize.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="HasStateChanged">
      <MemberSignature Language="C#" Value="public bool HasStateChanged { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool HasStateChanged" />
      <MemberSignature Language="DocId" Value="P:Microsoft.IdentityModel.Clients.ActiveDirectory.TokenCache.HasStateChanged" />
      <MemberSignature Language="VB.NET" Value="Public Property HasStateChanged As Boolean" />
      <MemberSignature Language="F#" Value="member this.HasStateChanged : bool with get, set" Usage="Microsoft.IdentityModel.Clients.ActiveDirectory.TokenCache.HasStateChanged" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.IdentityModel.Clients.ActiveDirectory</AssemblyName>
        <AssemblyVersion>3.16.0.14</AssemblyVersion>
        <AssemblyVersion>3.17.3.35304</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="f119d-118">Ruft ab oder legt das Flag, das angibt, ob der Cachestatus geändert wurde.</span><span class="sxs-lookup"><span data-stu-id="f119d-118">Gets or sets the flag indicating whether cache state has changed.</span></span> <span data-ttu-id="f119d-119">ADAL Methoden legen Sie dieses Flag nach jeder Änderung.</span><span class="sxs-lookup"><span data-stu-id="f119d-119">ADAL methods set this flag after any change.</span></span> <span data-ttu-id="f119d-120">Anwendung der Aufrufer sollte das Flag nach dem Serialisieren und Beibehalten des Zustands des Caches zurückgesetzt.</span><span class="sxs-lookup"><span data-stu-id="f119d-120">Caller application should reset the flag after serializing and persisting the state of the cache.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ReadItems">
      <MemberSignature Language="C#" Value="public virtual System.Collections.Generic.IEnumerable&lt;Microsoft.IdentityModel.Clients.ActiveDirectory.TokenCacheItem&gt; ReadItems ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.IdentityModel.Clients.ActiveDirectory.TokenCacheItem&gt; ReadItems() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.IdentityModel.Clients.ActiveDirectory.TokenCache.ReadItems" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function ReadItems () As IEnumerable(Of TokenCacheItem)" />
      <MemberSignature Language="F#" Value="abstract member ReadItems : unit -&gt; seq&lt;Microsoft.IdentityModel.Clients.ActiveDirectory.TokenCacheItem&gt;&#xA;override this.ReadItems : unit -&gt; seq&lt;Microsoft.IdentityModel.Clients.ActiveDirectory.TokenCacheItem&gt;" Usage="tokenCache.ReadItems " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.IdentityModel.Clients.ActiveDirectory</AssemblyName>
        <AssemblyVersion>3.16.0.14</AssemblyVersion>
        <AssemblyVersion>3.17.3.35304</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IEnumerable&lt;Microsoft.IdentityModel.Clients.ActiveDirectory.TokenCacheItem&gt;</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="f119d-121">Liest eine Kopie der Liste aller Elemente im Cache.</span><span class="sxs-lookup"><span data-stu-id="f119d-121">Reads a copy of the list of all items in the cache.</span></span> 
            </summary>
        <returns><span data-ttu-id="f119d-122">Die Elemente im cache</span><span class="sxs-lookup"><span data-stu-id="f119d-122">The items in the cache</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Serialize">
      <MemberSignature Language="C#" Value="public byte[] Serialize ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance unsigned int8[] Serialize() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.IdentityModel.Clients.ActiveDirectory.TokenCache.Serialize" />
      <MemberSignature Language="VB.NET" Value="Public Function Serialize () As Byte()" />
      <MemberSignature Language="F#" Value="member this.Serialize : unit -&gt; byte[]" Usage="tokenCache.Serialize " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.IdentityModel.Clients.ActiveDirectory</AssemblyName>
        <AssemblyVersion>3.16.0.14</AssemblyVersion>
        <AssemblyVersion>3.17.3.35304</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Byte[]</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="f119d-123">Serialisiert aktuellen Status des Caches als Blob.</span><span class="sxs-lookup"><span data-stu-id="f119d-123">Serializes current state of the cache as a blob.</span></span> <span data-ttu-id="f119d-124">Aufrufer-Anwendung kann das Blob beibehalten und den Status des Caches durch diese BLOBs zurück in den Konstruktor übergeben oder durch Aufrufen der Methode JavaScriptSerializer später aktualisieren.</span><span class="sxs-lookup"><span data-stu-id="f119d-124">Caller application can persist the blob and update the state of the cache later by passing that blob back in constructor or by calling method Deserialize.</span></span>
            </summary>
        <returns><span data-ttu-id="f119d-125">Aktuellen Status des Caches als blob</span><span class="sxs-lookup"><span data-stu-id="f119d-125">Current state of the cache as a blob</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>