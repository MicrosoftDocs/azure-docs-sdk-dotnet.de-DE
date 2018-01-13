<Type Name="MobileServicePrecisionCheckConverter" FullName="Microsoft.WindowsAzure.MobileServices.MobileServicePrecisionCheckConverter">
  <TypeSignature Language="C#" Value="public class MobileServicePrecisionCheckConverter : Newtonsoft.Json.JsonConverter" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit MobileServicePrecisionCheckConverter extends Newtonsoft.Json.JsonConverter" />
  <TypeSignature Language="DocId" Value="T:Microsoft.WindowsAzure.MobileServices.MobileServicePrecisionCheckConverter" />
  <TypeSignature Language="VB.NET" Value="Public Class MobileServicePrecisionCheckConverter&#xA;Inherits JsonConverter" />
  <TypeSignature Language="F#" Value="type MobileServicePrecisionCheckConverter = class&#xA;    inherit JsonConverter" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Mobile.Client</AssemblyName>
    <AssemblyVersion>4.0.0.0</AssemblyVersion>
    <AssemblyVersion>4.0.2.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Newtonsoft.Json.JsonConverter</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="ee51c-101">Eine Implementierung der <see cref="T:Newtonsoft.Json.JsonConverter" /> mit <see cref="T:System.Int64" />, <see cref="T:System.UInt64" /> und <see cref="T:System.Decimal" /> Eigenschaftentypen, die die Werte nur schreibt, wenn wir weiterhin Genauigkeit sicherstellen können nicht verloren, wenn der Wert serialisiert und an den Server gesendet.</span><span class="sxs-lookup"><span data-stu-id="ee51c-101">An implementation of <see cref="T:Newtonsoft.Json.JsonConverter" /> to be used with <see cref="T:System.Int64" />, <see cref="T:System.UInt64" /> and <see cref="T:System.Decimal" /> property types that only writes the values if we can ensure that precision will not be lost if the value is serialized and sent to the server.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public MobileServicePrecisionCheckConverter ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.MobileServices.MobileServicePrecisionCheckConverter.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Client</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.2.0</AssemblyVersion>
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
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.MobileServices.MobileServicePrecisionCheckConverter.CanConvert(System.Type)" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function CanConvert (objectType As Type) As Boolean" />
      <MemberSignature Language="F#" Value="override this.CanConvert : Type -&gt; bool" Usage="mobileServicePrecisionCheckConverter.CanConvert objectType" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Client</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.2.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="objectType" Type="System.Type" />
      </Parameters>
      <Docs>
        <param name="objectType"><span data-ttu-id="ee51c-102">Der zu überprüfende Typ.</span><span class="sxs-lookup"><span data-stu-id="ee51c-102">The type to check.</span></span></param>
        <summary>
            <span data-ttu-id="ee51c-103">Gibt an, ob der angegebene Typ von diesem Konverter konvertiert werden kann.</span><span class="sxs-lookup"><span data-stu-id="ee51c-103">Indicates if the specified type can be converted by this converter.</span></span>
            </summary>
        <returns><span data-ttu-id="ee51c-104">Einen booleschen Wert, der angibt, ob dieser Konverter den Typ konvertieren kann.</span><span class="sxs-lookup"><span data-stu-id="ee51c-104">A bool indicating if this converter can convert the type.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CanRead">
      <MemberSignature Language="C#" Value="public override bool CanRead { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool CanRead" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.MobileServices.MobileServicePrecisionCheckConverter.CanRead" />
      <MemberSignature Language="VB.NET" Value="Public Overrides ReadOnly Property CanRead As Boolean" />
      <MemberSignature Language="F#" Value="member this.CanRead : bool" Usage="Microsoft.WindowsAzure.MobileServices.MobileServicePrecisionCheckConverter.CanRead" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Client</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.2.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="ee51c-105">Bedeutet dies, dass <see cref="T:Newtonsoft.Json.JsonConverter" /> sollte nicht während der Deserialisierung verwendet werden.</span><span class="sxs-lookup"><span data-stu-id="ee51c-105">Indicates this <see cref="T:Newtonsoft.Json.JsonConverter" /> should not be used during deserialization.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ReadJson">
      <MemberSignature Language="C#" Value="public override object ReadJson (Newtonsoft.Json.JsonReader reader, Type objectType, object existingValue, Newtonsoft.Json.JsonSerializer serializer);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance object ReadJson(class Newtonsoft.Json.JsonReader reader, class System.Type objectType, object existingValue, class Newtonsoft.Json.JsonSerializer serializer) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.MobileServices.MobileServicePrecisionCheckConverter.ReadJson(Newtonsoft.Json.JsonReader,System.Type,System.Object,Newtonsoft.Json.JsonSerializer)" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function ReadJson (reader As JsonReader, objectType As Type, existingValue As Object, serializer As JsonSerializer) As Object" />
      <MemberSignature Language="F#" Value="override this.ReadJson : Newtonsoft.Json.JsonReader * Type * obj * Newtonsoft.Json.JsonSerializer -&gt; obj" Usage="mobileServicePrecisionCheckConverter.ReadJson (reader, objectType, existingValue, serializer)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Client</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.2.0</AssemblyVersion>
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
        <param name="reader"></param>
        <param name="objectType"></param>
        <param name="existingValue"></param>
        <param name="serializer"></param>
        <summary>
            <span data-ttu-id="ee51c-106">Lesen wird für diesen Konverter nicht unterstützt.</span><span class="sxs-lookup"><span data-stu-id="ee51c-106">Reading is not supported for this converter.</span></span>
            </summary>
        <returns />
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="WriteJson">
      <MemberSignature Language="C#" Value="public override void WriteJson (Newtonsoft.Json.JsonWriter writer, object value, Newtonsoft.Json.JsonSerializer serializer);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance void WriteJson(class Newtonsoft.Json.JsonWriter writer, object value, class Newtonsoft.Json.JsonSerializer serializer) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.MobileServices.MobileServicePrecisionCheckConverter.WriteJson(Newtonsoft.Json.JsonWriter,System.Object,Newtonsoft.Json.JsonSerializer)" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Sub WriteJson (writer As JsonWriter, value As Object, serializer As JsonSerializer)" />
      <MemberSignature Language="F#" Value="override this.WriteJson : Newtonsoft.Json.JsonWriter * obj * Newtonsoft.Json.JsonSerializer -&gt; unit" Usage="mobileServicePrecisionCheckConverter.WriteJson (writer, value, serializer)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Client</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.2.0</AssemblyVersion>
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
        <param name="writer">
            <span data-ttu-id="ee51c-107">Die JsonWriter-Instanz verwenden.</span><span class="sxs-lookup"><span data-stu-id="ee51c-107">The JsonWriter instance to use.</span></span>
            </param>
        <param name="value">
            <span data-ttu-id="ee51c-108">Der beim Schreiben zu prüfende Wert.</span><span class="sxs-lookup"><span data-stu-id="ee51c-108">The value to check on write.</span></span>
            </param>
        <param name="serializer">
            <span data-ttu-id="ee51c-109">Das aktuelle Serialisierungsprogramm.</span><span class="sxs-lookup"><span data-stu-id="ee51c-109">The current Serializer.</span></span>
            </param>
        <summary>
            <span data-ttu-id="ee51c-110">Schreibt die <paramref name="value" /> in Json nur, wenn sichergestellt ist, dass der Wert nicht verloren gehen Genauigkeit, wenn an den Server gesendet wird.</span><span class="sxs-lookup"><span data-stu-id="ee51c-110">Writes the <paramref name="value" /> to Json only if we can ensure that the value will not lose precision when sent to the server.</span></span>
            <span data-ttu-id="ee51c-111">Andernfalls wird eine Ausnahme ausgelöst.</span><span class="sxs-lookup"><span data-stu-id="ee51c-111">Otherwise it throws an exception.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>