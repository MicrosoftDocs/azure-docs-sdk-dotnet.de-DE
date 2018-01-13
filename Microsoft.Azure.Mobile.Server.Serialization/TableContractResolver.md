<Type Name="TableContractResolver" FullName="Microsoft.Azure.Mobile.Server.Serialization.TableContractResolver">
  <TypeSignature Language="C#" Value="public class TableContractResolver : Microsoft.Azure.Mobile.Server.Serialization.ServiceContractResolver" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit TableContractResolver extends Microsoft.Azure.Mobile.Server.Serialization.ServiceContractResolver" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Mobile.Server.Serialization.TableContractResolver" />
  <TypeSignature Language="VB.NET" Value="Public Class TableContractResolver&#xA;Inherits ServiceContractResolver" />
  <TypeSignature Language="F#" Value="type TableContractResolver = class&#xA;    inherit ServiceContractResolver" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Mobile.Server.Tables</AssemblyName>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Mobile.Server.Serialization.ServiceContractResolver</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="9f9a0-101">Diese Klasse implementiert eine <see cref="T:Newtonsoft.Json.Serialization.IContractResolver" /> zur Unterstützung für die Deserialisierung der <see cref="T:System.Web.Http.OData.Delta`1" /> -Typ angegeben, wobei JSON.NET.</span><span class="sxs-lookup"><span data-stu-id="9f9a0-101">This class implements an <see cref="T:Newtonsoft.Json.Serialization.IContractResolver" /> to provide support for deserialization of the <see cref="T:System.Web.Http.OData.Delta`1" /> type using JSON.NET.</span></span> 
            </summary>
    <remarks>
            <span data-ttu-id="9f9a0-102">Der Vertrag für erstellt <see cref="T:System.Web.Http.OData.Delta`1" /> werden Eigenschaften, die mit den Typen und die Eigenschaftsnamen des zugrunde liegenden Typs deserialisieren.</span><span class="sxs-lookup"><span data-stu-id="9f9a0-102">The contract created for <see cref="T:System.Web.Http.OData.Delta`1" /> will deserialize properties using the types and property names of the underlying type.</span></span> <span data-ttu-id="9f9a0-103">Die <see cref="T:Newtonsoft.Json.Serialization.JsonProperty" /> Instanzen werden kopiert, aus des zugrunde liegenden Typs <see cref="T:Newtonsoft.Json.Serialization.JsonContract" /> und angepasst, um ein dynamisches Objekt zu arbeiten.</span><span class="sxs-lookup"><span data-stu-id="9f9a0-103">The <see cref="T:Newtonsoft.Json.Serialization.JsonProperty" /> instances are copied from the underlying type's <see cref="T:Newtonsoft.Json.Serialization.JsonContract" /> and customized to work with a dynamic object.</span></span> <span data-ttu-id="9f9a0-104">Insbesondere wird eine benutzerdefinierte <see cref="T:Newtonsoft.Json.Serialization.IValueProvider" /> dient zum Abrufen und Festlegen von Werten, die mit dem Vertrag <see cref="T:System.Dynamic.DynamicObject" />, welche <see cref="T:System.Web.Http.OData.Delta`1" /> erbt.</span><span class="sxs-lookup"><span data-stu-id="9f9a0-104">In particular, a custom <see cref="T:Newtonsoft.Json.Serialization.IValueProvider" /> is used to get and set values using the contract of <see cref="T:System.Dynamic.DynamicObject" />, which <see cref="T:System.Web.Http.OData.Delta`1" /> inherits from.</span></span>
            </remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public TableContractResolver (System.Net.Http.Formatting.MediaTypeFormatter formatter);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Net.Http.Formatting.MediaTypeFormatter formatter) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Mobile.Server.Serialization.TableContractResolver.#ctor(System.Net.Http.Formatting.MediaTypeFormatter)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (formatter As MediaTypeFormatter)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Mobile.Server.Serialization.TableContractResolver : System.Net.Http.Formatting.MediaTypeFormatter -&gt; Microsoft.Azure.Mobile.Server.Serialization.TableContractResolver" Usage="new Microsoft.Azure.Mobile.Server.Serialization.TableContractResolver formatter" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Server.Tables</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="formatter" Type="System.Net.Http.Formatting.MediaTypeFormatter" />
      </Parameters>
      <Docs>
        <param name="formatter"><span data-ttu-id="9f9a0-105">Die <see cref="T:System.Net.Http.Formatting.MediaTypeFormatter" /> , die von diesem <see cref="T:Microsoft.Azure.Mobile.Server.Serialization.TableContractResolver" /> zugeordnet ist.</span><span class="sxs-lookup"><span data-stu-id="9f9a0-105">The <see cref="T:System.Net.Http.Formatting.MediaTypeFormatter" /> that this <see cref="T:Microsoft.Azure.Mobile.Server.Serialization.TableContractResolver" /> is associated with.</span></span></param>
        <summary>
            <span data-ttu-id="9f9a0-106">Initialisiert eine neue Instanz der dem <see cref="T:Microsoft.Azure.Mobile.Server.Serialization.TableContractResolver" /> -Klasse mit einer angegebenen <paramref name="formatter" />.</span><span class="sxs-lookup"><span data-stu-id="9f9a0-106">Initializes a new instance of the <see cref="T:Microsoft.Azure.Mobile.Server.Serialization.TableContractResolver" /> class with a given <paramref name="formatter" />.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateContract">
      <MemberSignature Language="C#" Value="protected override Newtonsoft.Json.Serialization.JsonContract CreateContract (Type objectType);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig virtual instance class Newtonsoft.Json.Serialization.JsonContract CreateContract(class System.Type objectType) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Mobile.Server.Serialization.TableContractResolver.CreateContract(System.Type)" />
      <MemberSignature Language="VB.NET" Value="Protected Overrides Function CreateContract (objectType As Type) As JsonContract" />
      <MemberSignature Language="F#" Value="override this.CreateContract : Type -&gt; Newtonsoft.Json.Serialization.JsonContract" Usage="tableContractResolver.CreateContract objectType" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Server.Tables</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Newtonsoft.Json.Serialization.JsonContract</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="objectType" Type="System.Type" />
      </Parameters>
      <Docs>
        <param name="objectType"><span data-ttu-id="9f9a0-107">Der Typ, den Vertrag für abgerufen werden soll.</span><span class="sxs-lookup"><span data-stu-id="9f9a0-107">The type to get the contract for.</span></span></param>
        <summary>
            <span data-ttu-id="9f9a0-108">Ruft den Vertrag für einen bestimmten Typ ab.</span><span class="sxs-lookup"><span data-stu-id="9f9a0-108">Gets the contract for a given type.</span></span> <span data-ttu-id="9f9a0-109">Der Typ <see cref="T:System.Web.Http.OData.Delta`1" /> wird behandelt, speziell, während alle anderen Typen von der Basisklasse behandelt werden.</span><span class="sxs-lookup"><span data-stu-id="9f9a0-109">The type <see cref="T:System.Web.Http.OData.Delta`1" /> is treated specially whereas all other types are handled by the base class.</span></span> 
            </summary>
        <returns><span data-ttu-id="9f9a0-110">Ein <see cref="T:Newtonsoft.Json.Serialization.JsonContract" /> für den angegebenen Typ.</span><span class="sxs-lookup"><span data-stu-id="9f9a0-110">A <see cref="T:Newtonsoft.Json.Serialization.JsonContract" /> for the given type.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetDeltaContract">
      <MemberSignature Language="C#" Value="protected virtual Newtonsoft.Json.Serialization.JsonContract GetDeltaContract (Type objectType);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig newslot virtual instance class Newtonsoft.Json.Serialization.JsonContract GetDeltaContract(class System.Type objectType) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Mobile.Server.Serialization.TableContractResolver.GetDeltaContract(System.Type)" />
      <MemberSignature Language="VB.NET" Value="Protected Overridable Function GetDeltaContract (objectType As Type) As JsonContract" />
      <MemberSignature Language="F#" Value="abstract member GetDeltaContract : Type -&gt; Newtonsoft.Json.Serialization.JsonContract&#xA;override this.GetDeltaContract : Type -&gt; Newtonsoft.Json.Serialization.JsonContract" Usage="tableContractResolver.GetDeltaContract objectType" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Server.Tables</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Newtonsoft.Json.Serialization.JsonContract</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="objectType" Type="System.Type" />
      </Parameters>
      <Docs>
        <param name="objectType"><span data-ttu-id="9f9a0-111">Der Typ, der einen Vertrag für bereitzustellen.</span><span class="sxs-lookup"><span data-stu-id="9f9a0-111">The type to provide a contract for.</span></span></param>
        <summary>
            <span data-ttu-id="9f9a0-112">Erstellt einen Vertrag für einen Typ von <see cref="T:System.Web.Http.OData.Delta`1" />.</span><span class="sxs-lookup"><span data-stu-id="9f9a0-112">Creates a contract for a type of <see cref="T:System.Web.Http.OData.Delta`1" />.</span></span>
            </summary>
        <returns><span data-ttu-id="9f9a0-113">Ein <see cref="T:Newtonsoft.Json.Serialization.JsonContract" /> für den angegebenen Typ.</span><span class="sxs-lookup"><span data-stu-id="9f9a0-113">A <see cref="T:Newtonsoft.Json.Serialization.JsonContract" /> for the given type.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>