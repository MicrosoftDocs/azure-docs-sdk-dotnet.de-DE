<Type Name="TwinJsonConverter" FullName="Microsoft.Azure.Devices.Shared.TwinJsonConverter">
  <TypeSignature Language="C#" Value="public sealed class TwinJsonConverter : Newtonsoft.Json.JsonConverter" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit TwinJsonConverter extends Newtonsoft.Json.JsonConverter" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Devices.Shared.TwinJsonConverter" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class TwinJsonConverter&#xA;Inherits JsonConverter" />
  <TypeSignature Language="F#" Value="type TwinJsonConverter = class&#xA;    inherit JsonConverter" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Devices.Shared</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Newtonsoft.Json.JsonConverter</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="0be06-101">Konvertiert <see cref="T:Microsoft.Azure.Devices.Shared.Twin" /> in Json</span><span class="sxs-lookup"><span data-stu-id="0be06-101">Converts <see cref="T:Microsoft.Azure.Devices.Shared.Twin" /> to Json</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public TwinJsonConverter ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Devices.Shared.TwinJsonConverter.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices.Shared</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>To be added.</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CanConvert">
      <MemberSignature Language="C#" Value="public override bool CanConvert (Type objectType);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance bool CanConvert(class System.Type objectType) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Devices.Shared.TwinJsonConverter.CanConvert(System.Type)" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function CanConvert (objectType As Type) As Boolean" />
      <MemberSignature Language="F#" Value="override this.CanConvert : Type -&gt; bool" Usage="twinJsonConverter.CanConvert objectType" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices.Shared</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="objectType" Type="System.Type" />
      </Parameters>
      <Docs>
        <param name="objectType">To be added.</param>
        <summary>
            <span data-ttu-id="0be06-102">Wert, der angibt, ob diese TwinJsonConverter JSON schreiben kann</span><span class="sxs-lookup"><span data-stu-id="0be06-102">Value indicating whether this TwinJsonConverter can write JSON</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CanRead">
      <MemberSignature Language="C#" Value="public override bool CanRead { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool CanRead" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Devices.Shared.TwinJsonConverter.CanRead" />
      <MemberSignature Language="VB.NET" Value="Public Overrides ReadOnly Property CanRead As Boolean" />
      <MemberSignature Language="F#" Value="member this.CanRead : bool" Usage="Microsoft.Azure.Devices.Shared.TwinJsonConverter.CanRead" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices.Shared</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="0be06-103">Konverter lesen können flag</span><span class="sxs-lookup"><span data-stu-id="0be06-103">Converter Can Read flag</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CanWrite">
      <MemberSignature Language="C#" Value="public override bool CanWrite { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool CanWrite" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Devices.Shared.TwinJsonConverter.CanWrite" />
      <MemberSignature Language="VB.NET" Value="Public Overrides ReadOnly Property CanWrite As Boolean" />
      <MemberSignature Language="F#" Value="member this.CanWrite : bool" Usage="Microsoft.Azure.Devices.Shared.TwinJsonConverter.CanWrite" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices.Shared</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="0be06-104">Wert, der angibt, ob diese TwinJsonConverter JSON gelesen werden kann</span><span class="sxs-lookup"><span data-stu-id="0be06-104">Value indicating whether this TwinJsonConverter can read JSON</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ReadJson">
      <MemberSignature Language="C#" Value="public override object ReadJson (Newtonsoft.Json.JsonReader reader, Type objectType, object existingValue, Newtonsoft.Json.JsonSerializer serializer);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance object ReadJson(class Newtonsoft.Json.JsonReader reader, class System.Type objectType, object existingValue, class Newtonsoft.Json.JsonSerializer serializer) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Devices.Shared.TwinJsonConverter.ReadJson(Newtonsoft.Json.JsonReader,System.Type,System.Object,Newtonsoft.Json.JsonSerializer)" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function ReadJson (reader As JsonReader, objectType As Type, existingValue As Object, serializer As JsonSerializer) As Object" />
      <MemberSignature Language="F#" Value="override this.ReadJson : Newtonsoft.Json.JsonReader * Type * obj * Newtonsoft.Json.JsonSerializer -&gt; obj" Usage="twinJsonConverter.ReadJson (reader, objectType, existingValue, serializer)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices.Shared</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Object</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="reader" Type="Newtonsoft.Json.JsonReader" />
        <Parameter Name="objectType" Type="System.Type" />
        <Parameter Name="existingValue" Type="System.Object" />
        <Parameter Name="serializer" Type="Newtonsoft.Json.JsonSerializer" />
      </Parameters>
      <Docs>
        <param name="reader"><span data-ttu-id="0be06-105">der Json-Reader.</span><span class="sxs-lookup"><span data-stu-id="0be06-105">the Json reader.</span></span></param>
        <param name="objectType"><span data-ttu-id="0be06-106">Objekttyp</span><span class="sxs-lookup"><span data-stu-id="0be06-106">object type</span></span></param>
        <param name="existingValue"><span data-ttu-id="0be06-107">vorhandene Wert</span><span class="sxs-lookup"><span data-stu-id="0be06-107">exisiting value</span></span></param>
        <param name="serializer"><span data-ttu-id="0be06-108">Das Json-Serialisierungsprogramm.</span><span class="sxs-lookup"><span data-stu-id="0be06-108">the Json serializer.</span></span></param>
        <summary>
            <span data-ttu-id="0be06-109">Konvertiert Json in die entsprechende <see cref="T:Microsoft.Azure.Devices.Shared.Twin" /> Darstellung.</span><span class="sxs-lookup"><span data-stu-id="0be06-109">Converts Json to its equivalent <see cref="T:Microsoft.Azure.Devices.Shared.Twin" /> representation.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="WriteJson">
      <MemberSignature Language="C#" Value="public override void WriteJson (Newtonsoft.Json.JsonWriter writer, object value, Newtonsoft.Json.JsonSerializer serializer);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance void WriteJson(class Newtonsoft.Json.JsonWriter writer, object value, class Newtonsoft.Json.JsonSerializer serializer) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Devices.Shared.TwinJsonConverter.WriteJson(Newtonsoft.Json.JsonWriter,System.Object,Newtonsoft.Json.JsonSerializer)" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Sub WriteJson (writer As JsonWriter, value As Object, serializer As JsonSerializer)" />
      <MemberSignature Language="F#" Value="override this.WriteJson : Newtonsoft.Json.JsonWriter * obj * Newtonsoft.Json.JsonSerializer -&gt; unit" Usage="twinJsonConverter.WriteJson (writer, value, serializer)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices.Shared</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="writer" Type="Newtonsoft.Json.JsonWriter" />
        <Parameter Name="value" Type="System.Object" />
        <Parameter Name="serializer" Type="Newtonsoft.Json.JsonSerializer" />
      </Parameters>
      <Docs>
        <param name="writer"><span data-ttu-id="0be06-110">der Json-Writer.</span><span class="sxs-lookup"><span data-stu-id="0be06-110">the Json writer.</span></span></param>
        <param name="value"><span data-ttu-id="0be06-111">Die <see cref="T:Microsoft.Azure.Devices.Shared.Twin" /> konvertieren.</span><span class="sxs-lookup"><span data-stu-id="0be06-111">the <see cref="T:Microsoft.Azure.Devices.Shared.Twin" /> to convert.</span></span></param>
        <param name="serializer"><span data-ttu-id="0be06-112">Das Json-Serialisierungsprogramm.</span><span class="sxs-lookup"><span data-stu-id="0be06-112">the Json serializer.</span></span></param>
        <summary>
            <span data-ttu-id="0be06-113">Konvertiert <see cref="T:Microsoft.Azure.Devices.Shared.Twin" /> in die entsprechende Json-Darstellung.</span><span class="sxs-lookup"><span data-stu-id="0be06-113">Converts <see cref="T:Microsoft.Azure.Devices.Shared.Twin" /> to its equivalent Json representation.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>