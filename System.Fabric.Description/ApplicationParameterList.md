<Type Name="ApplicationParameterList" FullName="System.Fabric.Description.ApplicationParameterList">
  <TypeSignature Language="C#" Value="public sealed class ApplicationParameterList : System.Collections.ObjectModel.KeyedCollection&lt;string,System.Fabric.Description.ApplicationParameter&gt;" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit ApplicationParameterList extends System.Collections.ObjectModel.KeyedCollection`2&lt;string, class System.Fabric.Description.ApplicationParameter&gt;" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.Description.ApplicationParameterList" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class ApplicationParameterList&#xA;Inherits KeyedCollection(Of String, ApplicationParameter)" />
  <TypeSignature Language="F#" Value="type ApplicationParameterList = class&#xA;    inherit KeyedCollection&lt;string, ApplicationParameter&gt;" />
  <AssemblyInfo>
    <AssemblyName>System.Fabric</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Collections.ObjectModel.KeyedCollection&lt;System.String,System.Fabric.Description.ApplicationParameter&gt;</BaseTypeName>
    <BaseTypeArguments>
      <BaseTypeArgument TypeParamName="!0">System.String</BaseTypeArgument>
      <BaseTypeArgument TypeParamName="!1">System.Fabric.Description.ApplicationParameter</BaseTypeArgument>
    </BaseTypeArguments>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
      <para><span data-ttu-id="b6a2d-101">Stellt die Liste der Parameter der Anwendung auf die aktuelle Version der Anwendung angewendet.</span><span class="sxs-lookup"><span data-stu-id="b6a2d-101">Represents the list of application parameters applied to the current version of the application.</span></span> <span data-ttu-id="b6a2d-102">Mit abgerufen <see cref="M:System.Fabric.FabricClient.QueryClient.GetApplicationListAsync(System.Uri)" />.</span><span class="sxs-lookup"><span data-stu-id="b6a2d-102">Retrieved using <see cref="M:System.Fabric.FabricClient.QueryClient.GetApplicationListAsync(System.Uri)" />.</span></span></para>
      <para><span data-ttu-id="b6a2d-103">Diese Klasse leitet sich von einem KeyedCollection, dessen Schlüssel den Namen des zugeordneten ApplicationParameter ist.</span><span class="sxs-lookup"><span data-stu-id="b6a2d-103">This class derives from a KeyedCollection whose string key is the name of the associated ApplicationParameter.</span></span></para>
    </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ApplicationParameterList ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Description.ApplicationParameterList.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
          <para><span data-ttu-id="b6a2d-104">Initialisiert eine neue Instanz der <see cref="T:System.Fabric.Description.ApplicationParameterList" />-Klasse.</span><span class="sxs-lookup"><span data-stu-id="b6a2d-104">Initializes a new instance of the <see cref="T:System.Fabric.Description.ApplicationParameterList" /> class.</span></span></para>
        </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ApplicationParameterList (System.Collections.Generic.IEqualityComparer&lt;string&gt; comparer);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Collections.Generic.IEqualityComparer`1&lt;string&gt; comparer) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Description.ApplicationParameterList.#ctor(System.Collections.Generic.IEqualityComparer{System.String})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (comparer As IEqualityComparer(Of String))" />
      <MemberSignature Language="F#" Value="new System.Fabric.Description.ApplicationParameterList : System.Collections.Generic.IEqualityComparer&lt;string&gt; -&gt; System.Fabric.Description.ApplicationParameterList" Usage="new System.Fabric.Description.ApplicationParameterList comparer" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="comparer" Type="System.Collections.Generic.IEqualityComparer&lt;System.String&gt;" />
      </Parameters>
      <Docs>
        <param name="comparer">
          <para><span data-ttu-id="b6a2d-105">Der Gleichheitsvergleich.</span><span class="sxs-lookup"><span data-stu-id="b6a2d-105">The equality comparer.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="b6a2d-106">Initialisiert eine neue Instanz der <see cref="T:System.Fabric.Description.ApplicationParameterList" />-Klasse.</span><span class="sxs-lookup"><span data-stu-id="b6a2d-106">Initializes a new instance of the <see cref="T:System.Fabric.Description.ApplicationParameterList" /> class.</span></span></para>
        </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ApplicationParameterList (System.Collections.Generic.IEqualityComparer&lt;string&gt; comparer, int dictionaryCreationThreshold);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Collections.Generic.IEqualityComparer`1&lt;string&gt; comparer, int32 dictionaryCreationThreshold) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Description.ApplicationParameterList.#ctor(System.Collections.Generic.IEqualityComparer{System.String},System.Int32)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (comparer As IEqualityComparer(Of String), dictionaryCreationThreshold As Integer)" />
      <MemberSignature Language="F#" Value="new System.Fabric.Description.ApplicationParameterList : System.Collections.Generic.IEqualityComparer&lt;string&gt; * int -&gt; System.Fabric.Description.ApplicationParameterList" Usage="new System.Fabric.Description.ApplicationParameterList (comparer, dictionaryCreationThreshold)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="comparer" Type="System.Collections.Generic.IEqualityComparer&lt;System.String&gt;" />
        <Parameter Name="dictionaryCreationThreshold" Type="System.Int32" />
      </Parameters>
      <Docs>
        <param name="comparer">
          <para><span data-ttu-id="b6a2d-107">Der Gleichheitsvergleich.</span><span class="sxs-lookup"><span data-stu-id="b6a2d-107">The equality comparer.</span></span></para>
        </param>
        <param name="dictionaryCreationThreshold">
          <para><span data-ttu-id="b6a2d-108">Der Schwellenwert für die Erstellung.</span><span class="sxs-lookup"><span data-stu-id="b6a2d-108">The creation threshold.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="b6a2d-109">Initialisiert eine neue Instanz der <see cref="T:System.Fabric.Description.ApplicationParameterList" />-Klasse.</span><span class="sxs-lookup"><span data-stu-id="b6a2d-109">Initializes a new instance of the <see cref="T:System.Fabric.Description.ApplicationParameterList" /> class.</span></span></para>
        </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetKeyForItem">
      <MemberSignature Language="C#" Value="protected override string GetKeyForItem (System.Fabric.Description.ApplicationParameter item);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig virtual instance string GetKeyForItem(class System.Fabric.Description.ApplicationParameter item) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Description.ApplicationParameterList.GetKeyForItem(System.Fabric.Description.ApplicationParameter)" />
      <MemberSignature Language="VB.NET" Value="Protected Overrides Function GetKeyForItem (item As ApplicationParameter) As String" />
      <MemberSignature Language="F#" Value="override this.GetKeyForItem : System.Fabric.Description.ApplicationParameter -&gt; string" Usage="applicationParameterList.GetKeyForItem item" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="item" Type="System.Fabric.Description.ApplicationParameter" />
      </Parameters>
      <Docs>
        <param name="item">
          <para><span data-ttu-id="b6a2d-110">Application-Parameter für den den Schlüssel abgerufen.</span><span class="sxs-lookup"><span data-stu-id="b6a2d-110">Application parameter for which to get the key.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="b6a2d-111">Ruft den Schlüsselnamen für den Parameter angegebene Anwendung ab.</span><span class="sxs-lookup"><span data-stu-id="b6a2d-111">Gets the key name for the specified application parameter.</span></span></para>
        </summary>
        <returns>
          <para><span data-ttu-id="b6a2d-112">Gibt den Namen des Schlüssels zurück.</span><span class="sxs-lookup"><span data-stu-id="b6a2d-112">Returns the key name.</span></span></para>
        </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ToString">
      <MemberSignature Language="C#" Value="public override string ToString ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance string ToString() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Description.ApplicationParameterList.ToString" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function ToString () As String" />
      <MemberSignature Language="F#" Value="override this.ToString : unit -&gt; string" Usage="applicationParameterList.ToString " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="b6a2d-113">Überschreibt die Methode ToString() an.</span><span class="sxs-lookup"><span data-stu-id="b6a2d-113">Overrides ToString() method.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="b6a2d-114">Gibt eine Zeichenfolge, die Parameter für alle Anwendungen und deren Werte angezeigt.</span><span class="sxs-lookup"><span data-stu-id="b6a2d-114">Returns a string that displays all applications parameters and their values.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>