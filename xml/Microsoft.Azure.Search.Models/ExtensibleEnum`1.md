<Type Name="ExtensibleEnum&lt;T&gt;" FullName="Microsoft.Azure.Search.Models.ExtensibleEnum&lt;T&gt;">
  <TypeSignature Language="C#" Value="public abstract class ExtensibleEnum&lt;T&gt; : IEquatable&lt;T&gt; where T : ExtensibleEnum&lt;T&gt;" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract beforefieldinit ExtensibleEnum`1&lt;(class Microsoft.Azure.Search.Models.ExtensibleEnum`1&lt;!T&gt;) T&gt; extends System.Object implements class System.IEquatable`1&lt;!T&gt;" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Search.Models.ExtensibleEnum`1" />
  <TypeSignature Language="VB.NET" Value="Public MustInherit Class ExtensibleEnum(Of T)&#xA;Implements IEquatable(Of T)" />
  <TypeSignature Language="F#" Value="type ExtensibleEnum&lt;'T (requires 'T :&gt; ExtensibleEnum&lt;'T&gt;)&gt; = class&#xA;    interface IEquatable&lt;'T (requires 'T :&gt; ExtensibleEnum&lt;'T&gt;)&gt;" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Search</AssemblyName>
    <AssemblyVersion>3.0.0.0</AssemblyVersion>
    <AssemblyVersion>4.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <TypeParameters>
    <TypeParameter Name="T">
      <Constraints>
        <BaseTypeName>Microsoft.Azure.Search.Models.ExtensibleEnum&lt;T&gt;</BaseTypeName>
      </Constraints>
    </TypeParameter>
  </TypeParameters>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces>
    <Interface>
      <InterfaceName>System.IEquatable&lt;T&gt;</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <typeparam name="T">To be added.</typeparam>
    <summary>
            <span data-ttu-id="7f744-101">Abstrakte Basisklasse für Typen, die Enumerationen fungieren, aber mit beliebigen Zeichenfolgenwerte erweitert werden können.</span><span class="sxs-lookup"><span data-stu-id="7f744-101">Abstract base class for types that act like enums, but can be extended with arbitrary string values.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="protected ExtensibleEnum (string name);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig specialname rtspecialname instance void .ctor(string name) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.Models.ExtensibleEnum`1.#ctor(System.String)" />
      <MemberSignature Language="VB.NET" Value="Protected Sub New (name As String)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Search.Models.ExtensibleEnum&lt;'T (requires 'T :&gt; Microsoft.Azure.Search.Models.ExtensibleEnum&lt;'T&gt;)&gt; : string -&gt; Microsoft.Azure.Search.Models.ExtensibleEnum&lt;'T (requires 'T :&gt; Microsoft.Azure.Search.Models.ExtensibleEnum&lt;'T&gt;)&gt;" Usage="new Microsoft.Azure.Search.Models.ExtensibleEnum&lt;'T (requires 'T :&gt; Microsoft.Azure.Search.Models.ExtensibleEnum&lt;'T&gt;)&gt; name" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="name"><span data-ttu-id="7f744-102">Der Wert für diese Instanz der erweiterbare Enumeration.</span><span class="sxs-lookup"><span data-stu-id="7f744-102">The value for this instance of the extensible enumeration.</span></span></param>
        <summary>
            <span data-ttu-id="7f744-103">Initialisiert eine neue Instanz der ExtensibleEnum-Klasse.</span><span class="sxs-lookup"><span data-stu-id="7f744-103">Initializes a new instance of the ExtensibleEnum class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Equals">
      <MemberSignature Language="C#" Value="public override bool Equals (object obj);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance bool Equals(object obj) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.Models.ExtensibleEnum`1.Equals(System.Object)" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function Equals (obj As Object) As Boolean" />
      <MemberSignature Language="F#" Value="override this.Equals : obj -&gt; bool" Usage="extensibleEnum.Equals obj" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="obj" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="obj">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <inheritdoc />
      </Docs>
    </Member>
    <Member MemberName="Equals">
      <MemberSignature Language="C#" Value="public bool Equals (T other);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance bool Equals(!T other) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.Models.ExtensibleEnum`1.Equals(`0)" />
      <MemberSignature Language="VB.NET" Value="Public Function Equals (other As T) As Boolean" />
      <MemberSignature Language="F#" Value="override this.Equals : 'T -&gt; bool" Usage="extensibleEnum.Equals other" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:System.IEquatable`1.Equals(`0)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="other" Type="T" />
      </Parameters>
      <Docs>
        <param name="other"><span data-ttu-id="7f744-104">Die ExtensibleEnum mit dem verglichen werden soll.</span><span class="sxs-lookup"><span data-stu-id="7f744-104">The ExtensibleEnum with which to compare.</span></span></param>
        <summary>
            <span data-ttu-id="7f744-105">Vergleicht die ExtensibleEnum Gleichheit mit einem anderen ExtensibleEnum an.</span><span class="sxs-lookup"><span data-stu-id="7f744-105">Compares the ExtensibleEnum for equality with another ExtensibleEnum.</span></span>
            </summary>
        <returns><span data-ttu-id="7f744-106">"true", wenn die ExtensibleEnum-Objekte gleich sind; "false" andernfalls.</span><span class="sxs-lookup"><span data-stu-id="7f744-106">true if the ExtensibleEnum objects are equal; false otherwise.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetHashCode">
      <MemberSignature Language="C#" Value="public override int GetHashCode ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance int32 GetHashCode() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.Models.ExtensibleEnum`1.GetHashCode" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function GetHashCode () As Integer" />
      <MemberSignature Language="F#" Value="override this.GetHashCode : unit -&gt; int" Usage="extensibleEnum.GetHashCode " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <inheritdoc />
      </Docs>
    </Member>
    <Member MemberName="Lookup">
      <MemberSignature Language="C#" Value="protected static T Lookup (string name);" />
      <MemberSignature Language="ILAsm" Value=".method familystatic hidebysig !T Lookup(string name) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.Models.ExtensibleEnum`1.Lookup(System.String)" />
      <MemberSignature Language="VB.NET" Value="Protected Shared Function Lookup (name As String) As T" />
      <MemberSignature Language="F#" Value="static member Lookup : string -&gt; 'T" Usage="Microsoft.Azure.Search.Models.ExtensibleEnum&lt;'T (requires 'T :&gt; Microsoft.Azure.Search.Models.ExtensibleEnum&lt;'T&gt;)&gt;.Lookup name" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>T</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="name"><span data-ttu-id="7f744-107">Der Name des ExtensibleEnum-Werts.</span><span class="sxs-lookup"><span data-stu-id="7f744-107">Name of the ExtensibleEnum value.</span></span></param>
        <summary>
            <span data-ttu-id="7f744-108">Sucht nach einer ExtensibleEnum-Instanz anhand des Namens, oder gibt null, wenn dem angegebenen Namen nicht mit der diese ExtensibleEnum den bekannten Werte übereinstimmt.</span><span class="sxs-lookup"><span data-stu-id="7f744-108">Looks up an ExtensibleEnum instance by name, or returns null if the given name does not match one of the known values of this ExtensibleEnum.</span></span>
            </summary>
        <returns><span data-ttu-id="7f744-109">Eine Instanz vom Typ "T" mit dem angegebenen Namen oder Null, wenn keine solche Instanz gefunden werden konnte.</span><span class="sxs-lookup"><span data-stu-id="7f744-109">An instance of type T with the given name, or null if no such instance could be found.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="op_Equality">
      <MemberSignature Language="C#" Value="public static bool operator == (Microsoft.Azure.Search.Models.ExtensibleEnum&lt;T&gt; lhs, T rhs);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig specialname bool op_Equality(class Microsoft.Azure.Search.Models.ExtensibleEnum`1&lt;!T&gt; lhs, !T rhs) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.Models.ExtensibleEnum`1.op_Equality(Microsoft.Azure.Search.Models.ExtensibleEnum{`0},`0)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Operator == (lhs As ExtensibleEnum(Of T), rhs As T) As Boolean" />
      <MemberSignature Language="F#" Value="static member ( = ) : Microsoft.Azure.Search.Models.ExtensibleEnum&lt;'T (requires 'T :&gt; Microsoft.Azure.Search.Models.ExtensibleEnum&lt;'T&gt;)&gt; * 'T -&gt; bool" Usage="lhs = rhs" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="lhs" Type="Microsoft.Azure.Search.Models.ExtensibleEnum&lt;T&gt;" />
        <Parameter Name="rhs" Type="T" />
      </Parameters>
      <Docs>
        <param name="lhs"><span data-ttu-id="7f744-110">Die erste ExtensibleEnum, verglichen werden soll.</span><span class="sxs-lookup"><span data-stu-id="7f744-110">The first ExtensibleEnum to compare.</span></span></param>
        <param name="rhs"><span data-ttu-id="7f744-111">Die zweite ExtensibleEnum, verglichen werden soll.</span><span class="sxs-lookup"><span data-stu-id="7f744-111">The second ExtensibleEnum to compare.</span></span></param>
        <summary>
            <span data-ttu-id="7f744-112">Vergleicht zwei ExtensibleEnum Werte hinsichtlich ihrer Gleichheit.</span><span class="sxs-lookup"><span data-stu-id="7f744-112">Compares two ExtensibleEnum values for equality.</span></span>
            </summary>
        <returns><span data-ttu-id="7f744-113">"true", wenn die ExtensibleEnum-Objekte gleich sind, oder null sind; "false" andernfalls.</span><span class="sxs-lookup"><span data-stu-id="7f744-113">true if the ExtensibleEnum objects are equal or are both null; false otherwise.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="op_Explicit">
      <MemberSignature Language="C#" Value="public static explicit operator string (Microsoft.Azure.Search.Models.ExtensibleEnum&lt;T&gt; name);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig specialname string op_Explicit(class Microsoft.Azure.Search.Models.ExtensibleEnum`1&lt;!T&gt; name) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.Models.ExtensibleEnum`1.op_Explicit(Microsoft.Azure.Search.Models.ExtensibleEnum{`0})~System.String" />
      <MemberSignature Language="VB.NET" Value="Public Shared Narrowing Operator CType (name As ExtensibleEnum(Of T)) As String" />
      <MemberSignature Language="F#" Value="static member op_Explicit : Microsoft.Azure.Search.Models.ExtensibleEnum&lt;'T (requires 'T :&gt; Microsoft.Azure.Search.Models.ExtensibleEnum&lt;'T&gt;)&gt; -&gt; string" Usage="Microsoft.Azure.Search.Models.ExtensibleEnum&lt;'T (requires 'T :&gt; Microsoft.Azure.Search.Models.ExtensibleEnum&lt;'T&gt;)&gt;.op_Explicit name" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="name" Type="Microsoft.Azure.Search.Models.ExtensibleEnum&lt;T&gt;" />
      </Parameters>
      <Docs>
        <param name="name"><span data-ttu-id="7f744-114">ExtensibleEnum konvertieren.</span><span class="sxs-lookup"><span data-stu-id="7f744-114">ExtensibleEnum to convert.</span></span></param>
        <summary>
            <span data-ttu-id="7f744-115">Definiert die explizite Konvertierung von ExtensibleEnum in eine Zeichenfolge.</span><span class="sxs-lookup"><span data-stu-id="7f744-115">Defines explicit conversion from ExtensibleEnum to string.</span></span>
            </summary>
        <returns><span data-ttu-id="7f744-116">Die ExtensibleEnum als Zeichenfolge.</span><span class="sxs-lookup"><span data-stu-id="7f744-116">The ExtensibleEnum as a string.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="op_Inequality">
      <MemberSignature Language="C#" Value="public static bool operator != (Microsoft.Azure.Search.Models.ExtensibleEnum&lt;T&gt; lhs, T rhs);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig specialname bool op_Inequality(class Microsoft.Azure.Search.Models.ExtensibleEnum`1&lt;!T&gt; lhs, !T rhs) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.Models.ExtensibleEnum`1.op_Inequality(Microsoft.Azure.Search.Models.ExtensibleEnum{`0},`0)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Operator != (lhs As ExtensibleEnum(Of T), rhs As T) As Boolean" />
      <MemberSignature Language="F#" Value="static member op_Inequality : Microsoft.Azure.Search.Models.ExtensibleEnum&lt;'T (requires 'T :&gt; Microsoft.Azure.Search.Models.ExtensibleEnum&lt;'T&gt;)&gt; * 'T -&gt; bool" Usage="Microsoft.Azure.Search.Models.ExtensibleEnum&lt;'T (requires 'T :&gt; Microsoft.Azure.Search.Models.ExtensibleEnum&lt;'T&gt;)&gt;.op_Inequality (lhs, rhs)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="lhs" Type="Microsoft.Azure.Search.Models.ExtensibleEnum&lt;T&gt;" />
        <Parameter Name="rhs" Type="T" />
      </Parameters>
      <Docs>
        <param name="lhs"><span data-ttu-id="7f744-117">Die erste ExtensibleEnum, verglichen werden soll.</span><span class="sxs-lookup"><span data-stu-id="7f744-117">The first ExtensibleEnum to compare.</span></span></param>
        <param name="rhs"><span data-ttu-id="7f744-118">Die zweite ExtensibleEnum, verglichen werden soll.</span><span class="sxs-lookup"><span data-stu-id="7f744-118">The second ExtensibleEnum to compare.</span></span></param>
        <summary>
            <span data-ttu-id="7f744-119">Vergleicht zwei Werte von ExtensibleEnum auf Ungleichheit.</span><span class="sxs-lookup"><span data-stu-id="7f744-119">Compares two ExtensibleEnum values for inequality.</span></span>
            </summary>
        <returns><span data-ttu-id="7f744-120">"true", wenn die ExtensibleEnum-Objekte nicht gleich sind; "false" andernfalls.</span><span class="sxs-lookup"><span data-stu-id="7f744-120">true if the ExtensibleEnum objects are not equal; false otherwise.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ToString">
      <MemberSignature Language="C#" Value="public override string ToString ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance string ToString() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.Models.ExtensibleEnum`1.ToString" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function ToString () As String" />
      <MemberSignature Language="F#" Value="override this.ToString : unit -&gt; string" Usage="extensibleEnum.ToString " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="7f744-121">Gibt eine Zeichenfolgendarstellung der ExtensibleEnum zurück.</span><span class="sxs-lookup"><span data-stu-id="7f744-121">Returns a string representation of the ExtensibleEnum.</span></span>
            </summary>
        <returns><span data-ttu-id="7f744-122">Die ExtensibleEnum als Zeichenfolge.</span><span class="sxs-lookup"><span data-stu-id="7f744-122">The ExtensibleEnum as a string.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>